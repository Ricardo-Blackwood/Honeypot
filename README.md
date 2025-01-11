# Honeypot setup with pentbox in kali Linux
Here we have the terminal, this is were we will create the honeypot


![honeypot](https://github.com/user-attachments/assets/f77966f0-9059-4394-93de-22251a99c0e6)


we use the "ifconfig" command to get sytsem configuration information like the IP address of our system 


![honeypot1 ](https://github.com/user-attachments/assets/629025b5-cb1b-4cbe-a15e-9a228d425675)


After getting the IP address we then move to pentbox using the "cd pentbox-1.8/" command


![honeypot2](https://github.com/user-attachments/assets/8dc1cae4-040d-47e2-9e03-9ea2d3799cb3)

pentbox is now open!

![honeypot3](https://github.com/user-attachments/assets/46fca75a-23c7-45a0-8db1-a803ac0c0fb2)

press the number "2" to activate the network tools section, then press "3" to create a honeypot then press "2" again to manually configure it 

![honeypot4](https://github.com/user-attachments/assets/b4a2bb80-7ccf-4eca-8c39-2f077f5d7096)

for the insert port section put "443" 

port 443 is use for HTTPS or secure web traffic on a browser.

insert the message "caught you!!" then press "y" to save 

![honeypot5](https://github.com/user-attachments/assets/7b01532c-d91f-4f78-bdd1-15116239d4e3)

for this section you can just press enter to skip logging the file name.

follow by "n" to deactivate the beep 

![honeypot6](https://github.com/user-attachments/assets/8fed654e-98ef-4680-8787-a63c9df3c4ca)

Your honeypot is now fully operational and ready to go!

![honeypot7](https://github.com/user-attachments/assets/8293568e-5449-43e8-9b9b-560ca427a334)

copy the IP address from the Eth0 after the ifconfig commmand and paste it into your browser with HTTPS:// (this ensures you on port 443)

![honeypot8](https://github.com/user-attachments/assets/021b615d-bb78-4f22-b96e-50c543f18d1c)

You'll observe a time out

![honeypot9](https://github.com/user-attachments/assets/9de1214e-602f-432b-bfb2-310b33b2ba4c)

And would you look at that! The IDS was activated warning you about potential intrusion!

use the "ctrl + C" in the terminal to exit pentbox 

![honeypot 10](https://github.com/user-attachments/assets/c6e11abb-5095-4536-b3fb-d3213741a80b)

A Honeypot, in the context of an organization's cybersecurity, involves creating an environment filled with potentially attractive digital assets and then observing how hackers attempt to gain access to them and what they do once they are inside the system.
