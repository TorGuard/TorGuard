# TorGuard
Everything around TorGuard VPN service. This is NOT official companies Repo of torguard.net, it is community based. For questions, email to torguard@i2pmail.org 

![TorGuard loves OpenWRT](https://i.imgur.com/nN9d9gM.png)
# TorGuard's OpenWRT VPN Luci App

***

### Requierments:
* OpenWrt (OpenWRT capable device) 
Find out if your device is capable to run OpenWRT and on which version. This addon was tested on latest release and on trunk version of OpenWRT
* You will need Luci webinterface. You can install it simply with this commands (All releases include WebIf, trunk versions do not)
`opkg install luci-ssl`
`/etc/init.d/uhttpd start`
`/etc/init.d/uhttpd enable`
* Openvpn Openssl packages and luci's openwpn app
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

### Screenshots of Openwrt's TorGuard VPN App for Luci WebIf
![Status Page](https://i.imgur.com/LLoXe1Q.png)

![Reboot Page](https://i.imgur.com/qmuR634.png)

![TorGuardVPN Page](https://i.imgur.com/st2e2sc.png)

![TorGuarn VPN Log Page](https://i.imgur.com/M1sjQKl.png)

![Config - Basic1 TorGuard_AUSTRALIA_AES128CBC_SHA256_TLS_Compression](https://i.imgur.com/RLfx0GP.png)

![Config - Basic2 TorGuard_AUSTRALIA_AES128CBC_SHA256_TLS_Compression](https://i.imgur.com/hmIXY6Z.png)

![Conig - Advanced - Sevice](https://i.imgur.com/k5QBM8n.png)

![Conig - Advanced - Networking](https://i.imgur.com/wUJ3Dub.png)

![Conig - Advanced - VPN](https://i.imgur.com/ws3nwwk.png)

![Conig - Advanced - Cryptography](https://i.imgur.com/iln1ZJm.png)

