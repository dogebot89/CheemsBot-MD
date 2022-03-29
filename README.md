<h1 align="center">ꪶ𝗖𝗵𝗲𝗲𝗺𝘀 𝗕𝗼𝘁-𝗠𝗗ꫂ<br></h1>
<p align="center">
  <img src="https://telegra.ph/file/8adfac9d34c43ce444fbf.jpg" width="540" height="300" />
</p>

<p align="center">
Cheems Bot Multi Device is a automated whatsapp bot created by <a href="https://github.com/dogebot89" target="_blank">Drips</a> using <a href="https://github.com/adiwajshing/Baileys" target="_blank">Baileys</a> and <a href="https://github.com/nodejs" target="_blank">Nodejs</a>. Dont forget to give a star bro.
</p>


# Setup For Deployment 👇

## `SETTINGS`

- CHANGE OWNER NUMBER [Here](https://github.com/dogebot89/CheemsBot-MD/blob/master/config/config.json#L25)
- CHANGE OWNER NAME [Here](https://github.com/dogebot89/CheemsBot-MD/blob/master/config/config.json#L30)
- CHANGE BOT NAME [Here](https://github.com/dogebot89/CheemsBot-MD/blob/master/config/config.json#L29)

## ` BUILDPACKS`

```
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
https://github.com/DuckyTeam/heroku-buildpack-imagemagick
heroku/nodejs
```

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/dogebot89/CheemsBot-MD/)

# Install Manually 👇
## `Requirements`
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip)
* [Libwebp](https://developers.google.com/speed/webp/download)
* Any text editor
## `Clone Repo & Installation dependencies`
```bash
git clone https://github.com/DGXeon/CheemsBot-MD.git
cd CheemsBot-MD
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
git clone https://github.com/dogebot89/CheemsBot-MD
cd CheemsBot-MD
npm start
```
## `For VPS`
```bash
apt install nodejs 
apt install git 
apt apt install ffmpeg 
apt apt install libwebp 
apt apt install imagemagick
apt install bash
git clone https://github.com/dogebot89/CheemsBot-MD
cd CheemsBot-MD
npm start
```
## `For 24/7 Activation`
```bash
npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs
```
