---
description: return current guild id
---

# $guildId

## Usage:

\[]

## Example:

```
$guildId[]
```

```
$send[$channelId[];$guildId[]]
```

## Command Example:

```javascript
bot.command({
    name: "guildid",
    code: `$send[$channelId[];$guildId[]]`
})
```
