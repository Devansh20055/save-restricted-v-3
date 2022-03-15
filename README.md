<h1 align="center">
  <b>Save restricted content Bot</b>
</h1> 

Contact: [Telegram](https://t.me/ITS_NOT_ROMEO)

A stable telegram bot to get restricted messages 

- works for both public and private channels
- Custom thumbnail support for Pvt medias
- supports text and webpage media messages
- Faster speed
- Forcesubscribe available 
- `/batch` - (For owner only) Use this command to save upto 100 files from a pvt or public restricted channel at once.
- Time delay is added to avoid FloodWait and keep user account safe. 

# Variables

- `API_ID`
- `API_HASH`
- `SESSION`
- `BOT_TOKEN` 
- `AUTH` - Owner user id
- `FORCESUB` - Public channel username without '@'. Don't forget to add bot in channel as administrator. 

# Get API & PYROGRAM string session from:
 
API: [API scrapper Bot](https://t.me/USETGSBOT) or [Telegram.org](https://my.telegram.org/auth)

PYROGRAM SESSION: [SessionGen Bot](https://t.me/STRING_GENERATOR_OP_BOT) or [![Run on Repl.it](https://replit.com/badge/github/vasusen-code/saverestrictedcontentbot)](https://replit.com/@SpEcHiDe/GenerateStringSession)

BOT TOKEN: @Botfather on telegram

# Deploy
  
- Fork the repo, and star it
- create app in heroku
- go to settings of app>> config vars>> add all variables
- add buildpacks
- connect to github and deploy
- turn on dynos
  
Buildpacks for manual deploy:

- `heroku/python`
- `https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git`
