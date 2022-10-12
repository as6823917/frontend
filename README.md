
A Telegram bot to send messages and medias to the subscribers directly through bot.

 - Authorized users of the bot can send messages (Texts or Media) within the bot.
 - Those who have started the bot, will receive the above posts.
 - Authorized users can get the subscriber count also.

<br>

## Deploy to Heroku:
<p align="left">
  <a href="https://heroku.com/deploy?template=https://github.com/as6823917/broadcastv3">
     <img height="30px" src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku">
  </a>
</p>

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/5tkHg8?referralCode=CAqQ6O)

## Variables:

* `API_HASH`    Your API Hash from my.telegram.org
* `API_ID`      Your API ID from my.telegram.org
* `BOT_TOKEN`   Your bot token from @BotFather
* `AUTH_USERS`  Create a list of User Ids to use this bot
* `DB_URI` Create a postgre database if you deploy the locally | In heroku do nothing  
* `SUPPORT_CHAT` Public group / channel username of the support chat

## @BotFather Commands
```
send - send posts to the subscribers (Admin Only)
subscribers - view subscribers count (Admin Only)
```




