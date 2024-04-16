# Advanced-Web-Panel
This project is only for personal learning and communication, please do not use it for illegal purposes, please do not use it in a production environment
If you think this project is helpful to you, you may wish to give a🌟

"Buy Me A Coffee"

USDT (TRC20): TYTq73Gj6dJ67qe58JVPD9zpjW2cc9XgVz
Quick Overview
Features	Enable?
Multi-Protocol	✔️
Multi-Language	✔️
Multi-Client/Inbound	✔️
Advanced Traffic Routing Interface	✔️
Client & Traffic & System Status	✔️
Subscription Service (link + info)	✔️
Dark/Light Theme	✔️
Default Installation Informarion
Panel Port: 2095
Panel Path: /app/
Subscription Port: 2096
Subscription Path: /sub/
User/Passowrd: admin
Install & Upgrade to Latest Version
bash <(curl -Ls https://raw.githubusercontent.com/alireza0/s-ui/master/install.sh)
Install Custom Version
Step 1: To install your desired version, add the version to the end of the installation command. e.g., ver 0.0.1:

bash <(curl -Ls https://raw.githubusercontent.com/alireza0/s-ui/master/install.sh) 0.0.1
Uninstall S-UI
systemctl disable sing-box --now
systemctl disable s-ui  --now

rm -f /etc/systemd/system/s-ui.service
rm -f /etc/systemd/system/sing-box.service
systemctl daemon-reload

rm -fr /usr/local/s-ui
Install using Docker
Click for details
Languages
English
Farsi
Chinese (Simplified)
Chinese (Traditional)
Features
Supported protocols:
General: Mixed, SOCKS, HTTP, HTTPS, Direct, Redirect, TProxy
V2Ray based: VLESS, VMess, Trojan, Shadowsocks
Other protocols: ShadowTLS, Hysteria, Hysteri2, Naive, TUIC
Supports XTLS protocols
An advanced interface for routing traffic, incorporating PROXY Protocol, External, and Transparent Proxy, SSL Certificate, and Port
An advanced interface for inbound and outbound configuration
Clients’ traffic cap and expiration date
Displays online clients, inbounds and outbounds with traffic statistics, and system status monitoring
Subscription service with ability to add external links and subscription
HTTPS for secure access to the web panel and subscription service (self-provided domain + SSL certificate)
Dark/Light theme
Recommended OS
CentOS 8+
Ubuntu 20+
Debian 10+
Fedora 36+
