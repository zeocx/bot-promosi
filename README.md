

<h1 align="center">ꪶVoidBotꫂ<br></h1>
<p align="center">
<img src="./XeonMedia/theme/Cheems-bot.gif" alt="animated" width="540" height="280" />
</p>

<p align="center">
Void Bot Multi Device is a automated whatsapp bot created by <a href="https://github.com/KioniNdungu" target="_blank">Void</a> using <a href="https://github.com/adiwajshing/Baileys" target="_blank">Baileys</a> and <a href="https://github.com/nodejs" target="_blank">Nodejs</a>. Dont forget to give a star bro.
</p>

------

# ```Bot Info```
<p align="center">
<a href="https://github.com/KioniNdungu/followers"><img title="Followers" src="https://img.shields.io/github/followers/KioniNdungu?color=red&style=flat-square"></a>
<a href="https://github.com/KioniNdungu/m/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/KioniNdungu/m?color=blue&style=flat-square"></a>
<a href="https://github.com/KioniNdungu/m/network/members"><img title="Forks" src="https://img.shields.io/github/forks/KioniNdungu/m?color=red&style=flat-square"></a>
<a href="https://github.com/KioniNdungu/m/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/KioniNdungu/m?label=Watchers&color=blue&style=flat-square"></a>
<a href="https://github.com/KioniNdungu/m"><img title="Open Source" src="https://img.shields.io/badge/Author-Void%20Bot%20Ke.-red?v=103"></a>
<a href="https://github.com/KioniNdungu/m/"><img title="Size" src="https://img.shields.io/github/repo-size/KioniNdungu/m?style=flat-square&color=green"></a>
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FKioniNdungu%2Fm&count_bg=%2379C83D&title_bg=%23555555&icon=probot.svg&icon_color=%2300FF6D&title=hits&edge_flat=false"/></a>
<a href="https://github.com/KioniNdungu/m/graphs/commit-activity"><img height="20" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg"></a>&nbsp;&nbsp;
</p>
<p align='center'>
    </p>

-------

# Setup For Deployment 👇

- FORK THE REPOSITORY [Here](https://github.com/KioniNdungu/m/fork)

## `Scan QR Code For Session`
[![Cheems Bot](https://repl.it/badge/github/quiec/whatsasena)](https://replit.com/@DGVoid/Cheems-Bot-Multi-Device-Qr-Code-Generator?output%20only=1&lite=1#index.js)

## `SETTINGS`

- CHANGE OWNER NUMBER VCARD [Here](https://github.com/KioniNdungu/m/blob/master/settings.js#L58)
- CHANGE OWNER NUMBER MENU [Here](https://github.com/KioniNdungu/m/blob/master/settings.js#L65)
- CHANGE OWNER NUMBER TAG [Here](https://github.com/KioniNdungu/m/blob/master/settings.js#L66)
- CHANGE OWNER NAME [Here](https://github.com/KioniNdungu/m/blob/master/settings.js#L59)
- CHANGE BOT NAME [Here](https://github.com/KioniNdungu/m/blob/master/settings.js#L67)

## ` BUILDPACKS`

```
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
```

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/KioniNdungu/m/)

# Install Manually 👇
## `Requirements`
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip)
* [Libwebp](https://developers.google.com/speed/webp/download)
* Any text editor
## `Clone Repo & Installation dependencies`
```bash
git clone https://github.com/KioniNdungu/m.git
cd m

npm start
```
## `For Termux/Ssh/Ubuntu`
```bash
apt update
apt upgrade
pkg update && pkg upgrade
pkg install bash
pkg install libwebp
pkg install git -y
pkg install nodejs -y 
pkg install ffmpeg -y 
pkg install wget
pkg install imagemagick -y
git clone https://github.com/KioniNdungu/m
cd m
npm start
```
## `For VPS`
```bash
apt install nodejs 
apt install git 
apt apt install ffmpeg 
apt apt install libwebp 
apt apt install imagrmagick
apt install bash
git clone https://github.com/KioniNdungu/m
cd m
npm start
```
## `For 24/7 Activation (Termux)`
```bash
npm i -g pm2 && pm2 start xeon.js && pm2 save && pm2 logs
```
