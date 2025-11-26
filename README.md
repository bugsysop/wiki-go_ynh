<h1>
  <!-- <img src="https://raw.githubusercontent.com/YunoHost/apps/main/logos/wiki-go.png" width="32px" alt="Logo of Wiki-Go"> -->
  Wiki-Go for YunoHost
</h1>

LeoMoon Wiki-Go is a simple, modern, feature-rich, flat-file based wiki platform using Markdown formating for content. It provides a clean, intuitive interface for creating and managing knowledge bases, documentation, and collaborative content. Built with Go and using no external database, this a low ressource system with zero maintenance and zero dependencies. 

## About this app

This branch is _only_ for configuration and customization of Wiko-Go instance on tmprs.net. 

Have in mind that actually there is _no_ official App Package to install Wiki-Go on Yunohost. 

Version: 1.7.5~ynh1

## Demo Site

You can try out Wiki-Go using the official live demo below. The demo site resets every hour, and all uploaded or edited content will be wiped automatically.

- 🔗 URL: https://wikigo.leomoon.com
- 👤 User: `admin`
- 🔒 Password: `demo123`

## Developer info

🛠️ Upstream Wiki-Go repository: <https://github.com/leomoon-studios/wiki-go>     
🛠️ Yunohost package repository: <https://github.com/YunoHost-Apps/wiki-go_ynh>    
🛠️ Yunohost packaging documentation: <https://doc.yunohost.org/packaging_apps>

## Install

This branch can be tested using the following commands.

Fresh install:
```
sudo yunohost app install https://github.com/bugsysop/wiki-go_ynh/tree/custom
```
Upgrade an existing install:
```
sudo yunohost app upgrade wiki-go -u https://github.com/bugsysop/wiki-go_ynh/tree/custom
```
