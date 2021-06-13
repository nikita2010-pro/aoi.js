# aoi.js


# This Package, allows you to make Discord Bot with ease!

## Are you Familiar with BDFD aka Bot Designer for Discord?

### Then you can easily transfer your code into this Package with no issues!



### Пример Использования

```js

const Aoijs = require("aoi.js")

const bot = new Aoijs.Bot({
token: "TOKEN YOUR BOT",
prefix: "PREFIX YOUR BOT"
})
bot.onMessage()
//commands(команды)

bot.command({
name: "ping", //Trigger(Триггер)
code: `$ping Pong!` //Code(Код)
})
```

## Slash Commands Support

With easy and simple functions, you can make Slash Commands with your Bots quick!

```js

bot.command({
