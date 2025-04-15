# VPN-router

Router Specification
Model: Netgear R6300v2
Firmware: Merlin 380.70_0-X7.9

Note: bought this router in 2020 with pre installed Merlin firmware. can't update the firmware as there isn't any stable release available.

##Astrill VPN router applet
###connection settings
GOTO administration >> System 
udpate the following options
**Persistent JFFS2 partition**
Format JFFS partition at next boot: No
Enable JFFS custom scripts and configs: Yes
**SSH Daemon**
Enable SSH: LAN + WAN
Allow SSH Port Forwarding: No
SSH service port: 22
Allow SSH password login: Yes
Enable SSH Brute Force Protection: No
###Get Astrill router applet 
login >> tools >> see all tools >> Router set-up >> copy the link

###Installtion Method
**using putty**
install putty software
connect SSH with telnet (need to enable the telnet feature from windows' "Turn Windows features on or off")
**using webshell**
goto koolshare softare center "koolshare - 软件中心"
install "shellinabox" or "webshell"
**installation**
use router username and password to connect
paste Astrill router applet link and hit enter to install
after completion, check router homepage
**NOTE:** replace astrouter.com with astroutercn.com





