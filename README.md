# 📰 WriteUpX App

## 👀 Requirements :
```yaml
- name : Python
    - type    : Programming Language
    - version : >= 3.10

- name : Go
    - type    : Programming Language
    - Version : >= 1.19

- name : MySQL
    - type : Database

- name : Git
    - type    : Tool
    - version : >= 2.39

- name : Linux
    - type : Distro
```

## 🦾 Features:
```yaml
- name : Social
    - Description : This App Will Send New Available WriteUps To [ Telegram ]

- name : resource
    - Description : WriteUps Will Send From Diffrent Tags Of medium.com

- name : System Log
    - Description : System Log Available in log/log.log

- name : Automated Configuration
    - Description : Automation Scripts To Config Your MySQL & Check [Files, Directories, Packages], Written in Python
```

## 🏁 ɪɴꜱᴛᴀʟʟᴀᴛɪᴏɴ:
```yaml
- Step One :
    - Description : Clone Repository
    - Command     : git clone https://github.com/nxenon/writeupx.git

- Step Two :
    - Description : Go To Project's Directory
    - Command     : cd writeupx

- Step Three :
    - Description : You Must Run Config Files
    - Commands : 
        - python3 -m pip install -r requirements.txt
        - python3 run.py

- Step Four :
    - Description : go run ./main.go
    - Command     : ./main
```


## ❓ ʜᴏᴡ ᴛᴏ ᴄʀᴇᴀᴛᴇ ᴛᴇʟᴇɢʀᴀᴍ ʙᴏᴛ
```yaml
- Step One :
    - Description : Go To BotFather : https://t.me/BotFather

- Step Two :
    - Description : Start The Bot
    - Command     : /start

- Step Three :
    - Description : Create New Bot
    - Command     : /newbot

- Step Four :
    - Description : Enter The Name For Your Bot
    - Example     : YoungBoy

- Step Five :
    - Description : Enter The Username For Your Bot
    - Example     : YoungBotBot

- Step Six :
    - Description : Now Copy Your Bot Token
    - Example     : 1234567890:XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
```

## ⚙️ Config .env File
```yaml
TELEGRAM_API=YOUR_TELEGRAM_API
CHANNEL_NAME=@YOUR_CHANNEL_ID
```

## ⚡️ Automate Write Up Sender
```yaml
- name : Crontab
    - Description : You Can Automate Process to Run main.go File
    - Example : With Below Code, You Can Run main.go Every 1 Hours
    - Command : 0 */1 * * * /usr/bin/go /PATH/TO/writeupx/main.go
    - Resource : https://geekflare.com/crontab-linux-with-real-time-examples-and-tools/
```

- This repo has been forked from user: [JesusKian](https://github.com/JesusKian)