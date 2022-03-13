# AXEL_VC_MUSIC_PLAYER
A Telegram Userbot to play Audio and Video songs / files in Telegram Voice Chats.

It's made with [PyTgCalls](https://github.com/pytgcalls/pytgcalls) and [Pyrogram](https://github.com/pyrogram/pyrogram)


[![logo](https://telegra.ph//file/4065c4735c15fefcd7afc.jpg)


## Requirements
- Python 3.8+
- FFMPEG
- Nodejs v16+

<a href="https://t.me/AXEL_SUPPPORTXD"><img src="https://img.shields.io/badge/Join-Telegram%20Channel-red.svg?logo=Telegram"></a>
<a href="https://t.me/AXEL_SUPPORT"><img src="https://img.shields.io/badge/Join-Telegram%20Group-blue.svg?logo=telegram"></a>
<a href="https://t.me/A_xe_l"><img src="https://img.shields.io/badge/AXEL -2cb6e0?style=for-the-badge&logo=telegram&logoColor=white"></a>

## Deployment

### Heroku 🥵
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

### Railway ❤
[![Deploy+on+Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https://github.com/S780821/Tg_Vc_MuzicPlayer&envs=API_ID,API_HASH,GROUP_MODE,HNDLR,SESSION)

### Local Deploy
1) Installing NodeJS
```bash
curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
sudo apt-get install -y nodejs
```

2) Installing FFMPEG and Git
```bash
sudo apt-get install git ffmpeg -y
```

3) Cloning the Repo
```bash
git clone https://github.com/AXELXDEV/AXEL_VC_PLAYER
cd AXEL_VC_PLAYER
```

4) Rename `example.env` to `.env` and Fill in the Environment Variables

5) Installing Requirements
```bash
pip3 install -U -r requirements.txt
```

6) Run the Bot
```bash
python3 main.py
```


## Environment Variables / Mandatory Variables
- `API_ID`
- `API_HASH`
- `SESSION` - A Pyrogram String Session. Get one from [Here](https://replit.com/@S780821/PyrogramSession)
- `HNDLR` - Your Userbot Handler (Default is !)
- `GROUP_MODE` - if Value is set to `True`, Anyone can Play. Set it to `False` to restrict play access to Sudo Users/Contacts only.


## Commands and Usage
1) Start the Userbot, check if the Userbot is running by `!ping`.
2) Commands of this userbot are accessible to and can be used by the Account itself and it's Contacts.
3) Check `!help` for commands.

- [SURAJOP7](https://github.com/SURAJOP7/AXEL.git) 

## Credits ✨
- [Dan](https://github.com/delivrance) for [Pyrogram](https://github.com/pyrogram/pyrogram)
- [Laky](https://github.com/Laky-64) for [PyTgCalls](https://github.com/pytgcalls/pytgcalls)
