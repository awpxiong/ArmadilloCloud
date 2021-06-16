# ArmadilloCloud
 ArmadilloCloud is a Debian Personal Cloud Storage that utilises Django Framework with remote access 24/7
 
 It is developed for a Final Year Project Solely on the purposes on having a personal cloud storage server that is mainly
 compatible in running it in a raspberry pi 4 Model B, the main goal of this project is to give individuals a sense of privacy, security,    confidentiality and furthermore a free software.

#This section is only if you are using a raspberry pi to run the server
ArmadilloCloud (ArmaCloud) is to be run an apache webserver
the only requirements is
1) You need to have your own Harddrive with any storage capacity (External Or Internal/ HDD or SSD), as ArmadilloCloud gives you the freedom of customisation (recommended to auto mount to avoid error)
2) You require Raspberry Pi 4 Model B (Atleast 4GB RAM)

The installer will assist in helping you to install the necessary dependencies.

**Setup Installation -**
Please Read the 'README!!!.txt' file within the zip folder for installation instructions
you are also required to edit the settings.py file within ArmaCloud/ArmaCloud/settings.py as you need to scroll down and enable
the following security settings if you wish to and add in your google mail account as a way to receive alerts of attempted logins

**FAQ **
1) Can't remotely access webserver from outside of LAN Network
Ans: Check if you have input your EXTERNAL ip address with port 80 or port 443 into the armacloud.conf in the 'servername', the external IP address can be, make sure you have port forwarded to port 80
verified using website such as www.whatismyip.com

2) ArmaCloud login or webpages is not being displayed on the webpage
Ans: please make sure that you have allow full access on the armacloud directory for apache with                                  'chown -R www-data:www-data /directory-of-armacloud/'

3) Login Attempt alert was not send to email account
Ans: Check if you have input a valid Google mail account username and password and Admins in 'settings.py' inside the ArmaCloud subdirectory

4) Unable to access apache webpages (Access denied)
Ans: check if you have allowed port forwarding to port 80 and allow all inbound and outbound if any firewall was enabled

######################

Disclaimer: I shall not be responsible for any criminal usage or illegal misuse of the software, for storing of illegal files/images or any obscene photos or stolen files that do not belong to the respective owner, anyone can store whatever files that want to at your own risk.

Whomever uses this free software has to agree to abide by the rules and laws of their own country of jurisdiction, storing of illegal files/photos is prohibited and no legal fault nor blames is to be issued to the developer of this software.
