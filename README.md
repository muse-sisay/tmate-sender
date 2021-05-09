<h1 align="center"> tmate sender</h1>


## INSTALLATION

- Install dependencies

```bash
$ sudo apt install tmate
```

## SETUP

Start by cloning this repo.

- Create telegram_bot using [Bot Father](https://t.me/botfather)  
[Guide](https://core.telegram.org/bots#6-botfather)

-  Get your chatID. Use this [bot](https://t.me/my_id_bot)

- Edit `tmateSender.sh`

edit token, chatID and network interface.

```txt
...
18 TOKEN= your-telegram-bot-token
19 CHAT_ID= chat-id
...
23 INTF= main-interface
...
```

- Add script to cron to start at reboot

```txt
@reboot ~/path/tmateSender.sh
```

## CUSTOMIZATION

- Change greeting


### TO DO 
- [ ] Use systemd than cron job
- [ ] script explanation

