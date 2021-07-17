## Bot Folders
![preview](https://cdn.discordapp.com/attachments/861244190461919246/865892847974612992/unknown.png)
## Bot Help Commands,using script file

![preview](https://cdn.discordapp.com/attachments/861244190461919246/865892938831757312/unknown.png)

## Help

I m using repl.it for host this bot + uptimer bot ,but you can use visual studio and more
If u use visual studio code you need to delete this from index.js:

require('http').createServer((req, res) => res.end('Bot is alive!')).listen(3000)


## How to install
If u want to install you have release page!


## How to put token

In repl.it you have Secrets( System environment variables ) 
Create a key with name Token and description Token

If u use visual studio code,delete .replit file and make a .env file and write Token=<yourtoken> or Token==<yourtoken>

Ok,now for Visual Studio Code users you have in index.js this: bot.login(mySecret); change the MySecret with process.env.Token

If the file give errors , search on google :))
