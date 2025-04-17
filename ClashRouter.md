# Clash VPN-router

### Router Specification
| Company | Model | type | Firmware | ver. |
| ------- | ----- |----- | -------- | ---- |
| Netgear | R6300v2 | armv7 | Merlin | 380.70_0-X7.9 |

Note: bought this router in 2020 with pre installed Merlin firmware. can't update the firmware as there isn't any stable release available.

## Get Subscription
use the following link to understand and buy about Clash subscription <br/>
https://github.com/ammasood12/clash

## Merlin Koolshare app
**Installation**  <br/>
1. Download Shadowsocks Koolshare app (shadowsocks.tar.gz) from https://github.com/cary-sas/v2ray_bin/releases <br/>
OR <br/>
Download Merlin Clash Koolshare app from https://t.me/merlinclashcat <br/>
2. use the offline installton in koolshare softare center "koolshare - 软件中心" <br/>
3. upload and install  <br/>

**Problems**  <br/>
1. unable to install software via koolshare offline installation  <br/>
2. install putty software and enable enable the telnet feature from windows' "Turn Windows features on or off" <br/>
3. Enable SSH in Administration > System
4. SSH into your router (you can use putty on windows, or terminal on Mac) and run the following command to enable offline innstallation:  <br/>
Can't use this command in "shellinabox" or "webshell" <br/>
> sed -i 's/\tdetect_package/\t# detect_package/g' /koolshare/scripts/ks_tar_install.sh <br/>

**Clash Usage Notes** <br/>
**Compatible with Merlin Clash** <br/>
Note: an established VPN connection required to get the subscription and run the ClashMerlin first time. <br/>
1. https://v2rayse.com -> have clash panel configs
2. SSone -> connect but can't browse
3. Ruk1ng001 -> use clash-yaml config to import, can't connect
4. YiFenJiChang ->  unsupport proxy type: hysteria2
Fix: use fake-ip in clash marlin



### How to use
check the following link <br/>
https://docs.wannaflix.net/routers/merlin/v2ray <br/>
Note: Don't use global mode. <br/>


