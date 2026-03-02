# ImgBB Image Uploader Telegram Bot

Telegram bot that uploads your photos to ImgBB and returns direct links.

## Features
- Send `/imageUrl` or `/start`
- Upload any photo → get ImgBB URL
- Handles high-res images

## Setup
1. Get [Telegram Bot Token](https://t.me/BotFather)
2. Get [ImgBB API Key](https://api.imgbb.com/)
3. `pip install -r requirements.txt`
4. Set env: `BOT_TOKEN`, `IMGBB_API_KEY`
5. `python bot.py`

## Deploy
- **Render**: Connect GitHub repo, add env vars [render.yaml]
- **Heroku**: `git push heroku main` [app.json]
- **Docker**: `docker build -t bot . && docker run -e BOT_TOKEN=... bot`

## requirements.txt

pyTelegramBotAPI
requests
![Demo](https://i.imgur.com/demo.png)  <!-- Add screenshot -->

License: MIT
