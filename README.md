# discord-message-mover
A bot that moves discord messages to another channel.

![](https://media.giphy.com/media/7JvnUU43b3kDyYUyoZ/giphy.gif)

## Installation
Requirements
- NodeJS
```
git clone https://github.com/mclarence/discord-message-mover
cd discord-message-mover
npm install
npm start (first configure settings below)
```
If you get the following error:
```
{ [Error: ENOENT: no such file or directory, scandir './events/']
  errno: -2,
  code: 'ENOENT',
  syscall: 'scandir',
  path: './events/' }
```
Ignore it or create an events directory in the root of the source code.

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
