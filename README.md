Forward your server's chat to your Telegram channel.
Psystec's Discord: discord. /EyRgFdA

## Features

* Global Chat forward.
* Team Chat forward.
* Notifies when a player connects or disconnects.
* Chat format can be customized.

## Permissions

To reload the config file with a console command you will need `chattotelegram.admin`

## Console Commands

- `chattotelegram` -- Displays the commands.
- `chattotelegram loadconfig` -- Loads the config file, handy for if you make changes in the config file.

## Configuration

 ```json
{
  "TelegramBotToken": "https://core.telegram.org/bots/features#creating-a-new-bot",
  "ChatID": "https://www.alphr.com/find-chat-id-telegram/",
  "EnableGlobalChat": true,
  "EnableTeamChat": true,
  "EnableConnections": true,
  "GlobalChatFormat": "[{time}] [**GLOBAL**] **{username}**: `{message}`",
  "TeamChatFormat": "[{time}] [**TEAM**] **{username}**: `{message}`",
  "ConnectionFormat": "[{time}] **{username}**: {connectionstatus}",
  "DateFormat": "yyyy-MM-dd HH:mm:ss"
}
```

## Localization

 ```json
{
  "Connected": "Connected.",
  "Disconnected": "Disconnected.",
  "NoPermission": "You do not have permission to use this command.",
  "FileLoaded": "File loaded.",
  "cmdCommand": "COMMAND",
  "cmdDescription": "DESCRIPTION",
  "cmdReload": "Reads the config file."
}
```

## Telegram Setup

1. Create a Telebram Bot using the BotFather to get the Bot Token.
2. Create a channel and change the public link.  (ex. t.me/ psystectest)
3. Use the Channel name as the ChatID config (ex. @psystectest)
