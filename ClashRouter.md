# Clash VPN-router

### Router Specification
| Company | Model | type | Firmware | ver. |
| ------- | ----- |----- | -------- | ---- |
| Netgear | R6300v2 | armv7 | Merlin | 380.70_0-X7.9 |

Note: bought this router in 2020 with pre installed Merlin firmware. can't update the firmware as there isn't any stable release available.

## Get Subscription
use the following link to understand and buy about Clash subscription <br/>
https://github.com/ammasood12/clash

### Installtion Method
1. download shadowsocks.tar.gz from the following link <br/>
https://github.com/cary-sas/v2ray_bin/releases <br/>
2. use the offline installton in koolshare softare center "koolshare - 软件中心" <br/>
3. upload and install  <br/>

**Problems**  <br/>
1. unable to install software via koolshare offline installation  <br/>
2. install putty software <br/>
3. connect SSH with telnet (need to enable the telnet feature from windows' "Turn Windows features on or off") <br/>
4. use following command in putty >> shell <br/>
Can't use this command in "shellinabox" or "webshell" <br/>
this will enable offline innstallation <br/>
> sed -i 's/\tdetect_package/\t# detect_package/g' /koolshare/scripts/ks_tar_install.sh <br/>


### How to use
check the following link <br/>
https://docs.wannaflix.net/routers/merlin/v2ray



