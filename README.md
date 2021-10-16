<p align="center">
	<img src="./Pp/IMG-20210827-WA0158.jpg" width="100%" style="margin-left: auto;margin-right: auto;display: block;">
</p>
<h1 align="center">Telegram Bot</h1>
<a href="https://github.com/Adiixyz"><img title="Createdby" src="https://img.shields.io/badge/Created-IAmAdyy-black?style=for-the-badge&logo=github"></a>
</p>

### Deploy to Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/IAmAdyy/TelegramBot)

### Run On Repl.It
[![Run on Repl.It](https://repl.it/badge/github/IAmAdyy/TelegramBot)](https://repl.it/github/IAmAdyy/TelegramBot)

<p align="center">
<a href="#"><img title="Telegram" 
src="https://img.shields.io/badge/Telegram%20Bot-red?colorA=red&colorB=%23017e40&style=for-the-badge"></a>
</p>

# INSTALLATION ( VPS )
```cmd
> apt install git -y
> apt install nodejs -y
> apt install npm -y [optional if npm not installed when installing nodejs]
> git clone https://github.com/IAmAdyy/TelegramBot
> cd TelegramBot
> npm i
> node .
```

# INSTALLATION ( TERMUX )
```cmd
> pkg install git -y
> pkg install nodejs -y
> git clone https://github.com/IAmAdyy/TelegramBot
> cd TelegramBot
> npm i
> node .
```
#### Note.. Use `apt` instead if `pkg` not work


# INSTALLATION ( WINDOWS, RDP )
Install these packages
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
```cmd
> git clone https://github.com/IAmAdyy/TelegramBot
> cd TelegramBot
> npm i
> node .
```

## Edit required value in `config.json`
```json
{
    "apikey": "LOLHUMAN_APIKEY",
    "bot_token": "",
    "owner": "IAmAdyy",
    "ownerLink": "https://t.me/IAmAdyyz",
    "version": "1.1.0",
    "prefix": "/"
}
```

* `apikey` : LolHuman Apikey. Get the apikey at [LolHuman](https://api.lolhuman.xyz)
* `bot_token` : Bot Token.. Get from [@BotFather](https://t.me/BotFather)
* `owner` : Owner Name
* `ownerLink` : Owner Link
* `Prefix` : Prefix for command... / Is default prefix

# Thanks To
- LolHuman
- Telegraf
- Adiixyz
