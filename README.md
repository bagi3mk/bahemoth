<h2 align="center">Telegram müzik botu</h2>
<p>
Telegramda müzik veya video akışı için telgraf botu
powered by <a href="https://github.com/pytgcalls/pytgcalls">PyTgCalls</a>
and <a href="https://github.com/pyrogram/pyrogram">Pyrogram</a>
</p>

<

<h3>Help Need </h3>
<div>
    Help me to translate this repo, click the localized button <br /> 
    <br/>
    <a title="Crowdin" target="_blank" href="https://crowdin.com/project/solid-music"><img src="https://badges.crowdin.net/solid-music/localized.svg"></a>
</div>

<h3>Features</h3> 
<ul>
    <li>Playlist features</li>
    <li>Multi Language</li>
    <li>Maintained</li>
    <li>Less environment variables</li>
</ul>

<h3>Telegram</h3>
<ul>
    <a href="https://t.me/SpotifyBots"><img alt="Spotify Channel" src="https://img.shields.io/badge/SpotifyBots-Channel-blue.svg?logo=telegram"></a> <br/>
    <a href="https://t.me/SpotifyBotss"><img alt="Spotify Support" src="https://img.shields.io/badge/SpotifyBots-Support-blue.svg?logo=telegram"></a> <br/>
</ul>

<h3>Deploy to Heroku </h3>
<div>
    <p align="center"><a href="https://heroku.com/deploy?template=https://github.com/Spotifyxy/sipsifa"><img src="https://img.shields.io/badge/DECODE-HEROKU-blue?style=plastic&logo=heroku&logoColor=yellow"width="400"heigh="8000" /></a></p>
</div>

### Deploy to VPS
```
$ sudo su
# apt-get update && apt-get upgrade -y
# apt-get install curl
# curl -sL https://deb.nodesource.com/setup_16.x | bash - 
# apt-get install ffmpeg python3-pip python3-virtualenv nodejs -y 
# git clone https://github.com/doellbarr/solidmusic && cd solidmusic 
# virtualenv venv && . venv/bin/activate 
# pip3 install --no-cache-dir -r requirements.txt 
# cp sample.env .env 
# nano .env # fill it with your env 
# python3 main.py
```
