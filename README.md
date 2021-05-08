# <h2><b><u>DIGITALMUSIXBOT</u></b></h2>

![BOT](https://telegra.ph/file/dd0ed8200ca6ae56affba.jpg)

## Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/sakhaavvaavaj93/digitalmusixbot)

## Manually

```# Telegram API Key
# get from https://my.telegram.org/apps
export API_ID="1234567"
export API_HASH="0123456789abcdef0123456789abcdef"

# Telegram Bot Token
# get from https://t.me/BotFather
export BOT_TOKEN="123456:ABC-DEF1234ghIkl-zyx57W2v1u123ew11"

# One or more user/group username/id the bot serve to,
# separate with space
export MUSIC_CHATS="-100123456789 username"

# install ffmpeg
apt install ffmpeg

virtualenv venv
venv/bin/pip install -U -r requirements.txt
venv/bin/python tgmusicbot.py```

## License

AGPL-3.0-or-later
