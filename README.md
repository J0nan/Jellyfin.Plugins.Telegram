# Jellyfin.Plugins.Telegram

⚠⚠ AS OF JELLYFIN 10.9 THIS NO LONGER WORKS ⚠⚠

Telegram bot Notification Agent for Jellyfin

Get started with Jellyfin at https://jellyfin.github.io/

## How to install
* Download the latests release
* Extract it
* Create a folder in the plugins folder. On windows it is usually in `C:\ProgramData\Jellyfin\Server\plugins`
* Copy the extracted files to the new folder
* Reboot Jellyfin

## How to use

* Create a bot (or use an existing one). You can use the `/newbot` command of BotFather for this. Make sure to copy the access token.
* Start the bot (by sending the `/start` command).
* Say something to your bot (a simple hello will suffice).
* Get your Chat Id. You can GET this URL: `https://api.telegram.org/bot<<YOUR TOAKEN>>/getUpdates`. Of course you will need to replace `<<YOUR TOKEN>>` with your token. In the answer, copy the `chat_id`.
* Now enable the plugin in Jellyfin specifiyng both the access token and the chat id. Enable, save the configuration and test it. If everything is ok you will receive the test notification in your bot.
* Profit!
