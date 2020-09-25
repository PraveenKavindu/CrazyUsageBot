# 🔥 CRAZYUSAGE_BOT 🔥 <br>
https:/t,me/edmgangx

<p align="center">
    <a href="https://github.com/PraveenKavindu/CrazyUsageBot">
        <img src="https://telegra.ph/file/df341e393aeda55112d3c.jpg" alt="CrazyUsage">
    </a>
    <br>
    <b>Pluggable Telegram UserBot</b>

# Userge 🔥

[![Build Status](https://travis-ci.com/UsergeTeam/Userge.svg?branch=dev)](https://travis-ci.com/UsergeTeam/Userge) ![Python Version](https://img.shields.io/badge/python-3.8-lightgrey) ![Release](https://img.shields.io/github/v/release/UsergeTeam/Userge) ![Stars](https://img.shields.io/github/stars/UsergeTeam/Userge) ![Forks](https://img.shields.io/github/forks/UsergeTeam/Userge) ![Issues Open](https://img.shields.io/github/issues/UsergeTeam/Userge) ![Issues Closed](https://img.shields.io/github/issues-closed/UsergeTeam/Userge) ![PR Open](https://img.shields.io/github/issues-pr/UsergeTeam/Userge) ![PR Closed](https://img.shields.io/github/issues-pr-closed/UsergeTeam/Userge) ![Contributors](https://img.shields.io/github/contributors/UsergeTeam/Userge) ![Repo Size](https://img.shields.io/github/repo-size/UsergeTeam/Userge) ![License](https://img.shields.io/github/license/UsergeTeam/Userge) ![Commit Activity](https://img.shields.io/github/commit-activity/m/UsergeTeam/Userge) [![Plugins Repo!](https://img.shields.io/badge/Plugins%20Repo-!-orange)](https://github.com/UsergeTeam/Userge-Plugins) [![Join Channel!](https://img.shields.io/badge/Join%20Channel-!-red)](https://t.me/theUserge) [![DeepSource](https://static.deepsource.io/deepsource-badge-light-mini.svg)](https://deepsource.io/gh/UsergeTeam/Userge/?ref=repository-badge)

> **Userge** is a Powerful , _Pluggable_ Telegram UserBot written in _Python_ using [Pyrogram](https://github.com/pyrogram/pyrogram).


## Features 😍

* Powerful and Very Useful **built-in** Plugins
  * gdrive [ upload / download / etc ] ( Team Drives Supported! ) 🤥
  * zip / tar / unzip / untar / unrar
  * telegram upload / download
  * pmpermit / afk
  * notes / filters
  * split / combine
  * gadmin
  * plugin manager
  * etc...
* Channel & Group log support
* Database support
* Build-in help support
* Easy to Setup & Use
* Easy to add / port Plugins
* Easy to write modules with the modified client

## Example Plugin 🤨

```python
from userge import userge, Message

LOG = userge.getLogger(__name__)  # logger object

CHANNEL = userge.getCLogger(__name__)  # channel logger object

@userge.on_cmd("test", about="help text to this command")  # adding handler and help text to .test command
async def testing(message: Message):
   LOG.info("starting test command...")  # log to console

   await message.edit("testing...", del_in=5)  # this will be automatically deleted after 5 sec

   await CHANNEL.log("testing completed!")  # log to channel
```

## Requirements 🥴

* Python 3.8 or Higher 👻
* Telegram [API Keys](https://my.telegram.org/apps)
* Google Drive [API Keys](https://console.developers.google.com/)
* MongoDB [Database URL](https://cloud.mongodb.com/)

## How To Deploy 👷

* **[HEROKU](https://www.heroku.com/) Method** 🔧

  > First click the button below. 

  > If you don't have HU_STRING_SESSION just ignore it.  

  > After Deployed to Heroku first turn off the app (resources -> turn off) and run `bash genStr` in console (more -> run console).  

  > After that copy the string session and past it in Config Vars (settings -> reveal config vars). 

  > Finally turn on the app and check the logs (settings -> view logs) :)

  [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/PraveenKavindu/CrazyUsageBot/tree/PRAVEEN)

* **Other Method** 🔧

> Head over to the [Join Group](https://t.me/edmgangx) and [Update Master](https://t.me/xcrazyhackerx7)
