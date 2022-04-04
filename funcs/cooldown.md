---
description: make cooldown for author id in this guild use {getTime} to get the time
---

# $cooldown

## Usage:

\[time in ms;error message]

## Example:

```js
$send[$channelId[];hi]
$cooldown[3000;don't spam, wait for {getTime}]
```

## Example Command:

```javascript
bot.command({
    name: "hi",
    code: `$send[$channelId[];hi]
$cooldown[3000;don't spam, wait for {getTime}]`
})

// {getTime} will issue how much time until the cooldown stops.
```
