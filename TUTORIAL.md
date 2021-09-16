## Requirements
- Your Discord Bot Token, if you don't know how to get a bot token read this [Guide](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)
- Node.js v12.0.0 or newer
- Packages you need to install: Discord.JS, better-sqlite3, canvas or canvacord, fs.
- DB Browser (SQLite) *(If you wish to see what's in the db)*

***Important: Do not share your bot token publicly!⚠***

## Installation
- Before running everything, you must have [node.js](https://nodejs.org/en/download/) installed
- To install [better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) you must have [Python](https://www.python.org/downloads/) installed in order to work.

## Config.json
Rename your `config.example.json` to `config.json`, then fill in the `token`, `ownerID`, `prefix` 

```
{
	"token": "your top secret bot token",
	"ownerID": "your ID here",
	"prefix": ">"
}
```

## Permissions
- ATTACH_FILES 
- SEND_MESSAGES 
- MESSAGE_EMBED or EMBED_LINKS 
- MANAGE_ROLES 

## Run the bot
- Run `npm install` to install all of uninstalled packages
- Run `node index.js` or `node .`
