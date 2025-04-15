# VPN-router

### Router Specification
| Company | Model | type | Firmware | ver. |
| ------- | ----- |----- | -------- | ---- |
| Netgear | R6300v2 | armv7 | Merlin | 380.70_0-X7.9 |

Note: bought this router in 2020 with pre installed Merlin firmware. can't update the firmware as there isn't any stable release available.

## Astrill VPN router applet
### connection settings
GOTO administration >> System <br/>
udpate the following options <br/>
**Persistent JFFS2 partition** <br/>
Format JFFS partition at next boot: No <br/>
Enable JFFS custom scripts and configs: Yes <br/>
**SSH Daemon** <br/>
Enable SSH: LAN + WAN <br/>
Allow SSH Port Forwarding: No <br/>
SSH service port: 22 <br/>
Allow SSH password login: Yes <br/>
Enable SSH Brute Force Protection: No <br/>
###Get Astrill router applet  <br/>
login >> tools >> see all tools >> Router set-up >> copy the link <br/>

### Installtion Method
**using putty** <br/>
install putty software <br/>
connect SSH with telnet (need to enable the telnet feature from windows' "Turn Windows features on or off") <br/>
**using webshell** <br/>
goto koolshare softare center "koolshare - 软件中心" <br/>
install "shellinabox" or "webshell" <br/>
**installation** <br/>
use router username and password to connect <br/>
paste Astrill router applet link and hit enter to install <br/>
after completion, check router homepage <br/>
**NOTE:** replace astrouter.com with astroutercn.com <br/>
