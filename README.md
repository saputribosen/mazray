<p align="center">
  <a href="https://github.com/gozargah/marzban" target="_blank" rel="noopener noreferrer">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github.com/Gozargah/Marzban-docs/raw/master/screenshots/logo-dark.png">
      <img width="160" height="160" src="https://github.com/Gozargah/Marzban-docs/raw/master/screenshots/logo-light.png">
    </picture>
  </a>
</p>
## Tested Ubuntu 20.04 <br>
Link github Original (https://github.com/Gozargah/Marzban) which added nginx so that vmess can be multipath and all can be ssl + nonssl
  
  ```html
 apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && reboot
 ```
 ```html
 wget https://raw.githubusercontent.com/saputribosen/mazray/main/sslmar.sh && chmod 755 sslmar.sh && ./sslmar.sh
 ```
OR
 ```html
apt update -y && apt install wget screen -y && wget -q https://raw.githubusercontent.com/saputribosen/mazray/main/sslmar.sh && chmod +x sslmar.sh && screen -S sslmar ./sslmar.sh
```

 NO HAVEE
  You must have a domain first
 
Open web panel http://yourdomain:8880/dashboard <br>
user: admin <br>
pass: admin

user pass panel can be changed with the command
```html
nano /root/marzban/env
 ```
After saving, please go to the marzban folder with
```html
cd /root/marzban
 ```
next
```html
docker compose down && docker compose up -d
 ```
 
 When you log in, set the host in the top right menu <br>
 ![Screenshot_20230404-154004_Termius](https://raw.githubusercontent.com/saputribosen/mazray/main/vmess.jpg)
 ![Screenshot_20230404-154004_Termius](https://raw.githubusercontent.com/saputribosen/mazray/main/vless.jpg)
 ![Screenshot_20230404-154004_Termius](https://raw.githubusercontent.com/saputribosen/mazray/main/trojan.jpg)
 ![Screenshot_20230404-154004_Termius](https://raw.githubusercontent.com/saputribosen/mazray/main/shadowsock.jpg)
 <br>
 idnusa.aryok.my.id, change with your domain <br> <br>
 For help? PM me :<a href="https://t.me/aryobrokoly" target=”_blank”><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=Telegram&label=Telegram&message=Click%20Here&color=blue"></a><br>
<br>
https://www.youtube.com/watch?v=b88tR_OtMGw

