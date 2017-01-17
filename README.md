# TorGuard
Everything around TorGuard VPN service. This is NOT official companies Repo of torguard.net, it is community based. For questions, email to torguard@i2pmail.org 

![TorGuard loves OpenWRT](https://i.imgur.com/nN9d9gM.png)
# TorGuard's OpenWRT VPN Luci App

***

### Requierments:
* OpenWrt (OpenWRT capable device) 
Find out your device is capable to run OpenWRT and which version. This addon was tested on latest release and on trunk
* You need Luci webinterface, you can install it simply with (All releases include WebIf, trunk version do not)
`opkg install luci-ssl`
`/etc/init.d/uhttpd start`
`/etc/init.d/uhttpd enable`
* Openvpn Openssl package and luci's openwpn app
`opkg install openvpn-openssl luci-app-openvpn`
**Oneliner for all requierments**:
`opkg update;opkg install luci-ssl openvpn-openssl luci-app-openvpn;/etc/init.d/uhttpd enable;/etc/init.d/uhttpd start`

***


### Installation Instruction:
1. Upload package to your server or clone from git `git clone https://github.com/TorGuard/TorGuard/luci-app-torguard.git`
1. Reboot `reboot -f`


### Important Wiki Links
* **COMMING SOON**


### Discussion Links
* **COMMING SOON**


### Affilate Links
* **COMMING SOON**
