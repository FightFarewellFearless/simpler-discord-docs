# How to setup?

read this example:

```javascript
const simple = require("easier-discord.js");

const bot = new simple.Bot({
  intents: ["GUILDS", "GUILD_MESSAGES"], //discord intents
  prefix: "!", // your bot prefix
});

bot.onMessage(); // callbacks that can trigger command when message is send

bot.command({
  name: "ping", //ping command
  code: `$send[$channelID[];Pong: $ping[]ms]`, //will return ping
});

bot.login("token"); // your bot token
```

{% hint style="warning" %}
**⚠️ Information:**

you need \[] for every functions to get execute even there's no params needed
{% endhint %}

### functions

for functions list, check in functions category
