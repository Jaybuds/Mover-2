# discord-message-mover
A bot that moves discord messages to another channel.

## Installation
```
git clone https://github.com/mclarence/discord-message-mover
cd discord-message-mover
npm install
npm start (first configure settings below)
```
## Configuration
All bot settings are stored in the config.json file.

`prefix` - The command prefix.

`token` - The discord bot token.

`modrole` - The the role that the user should have to run the bot.

## Usage
`{prefix}move <message_id> <channel_id>`

To obtain `message_id` right click the message you want to move and click 'Copy ID'

To obtain `channel_id` simply mention the channel you want to move the message into.

Example:
`$move 34092384923032 #anotherchannel`
