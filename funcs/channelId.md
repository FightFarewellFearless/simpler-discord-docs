---
description: return current channel id
---

# $channelId

## Usage:

\[]

## Example:

```
$channelId[]
```

```
$send[$channelId[];$channelId[]]
```

## Example Command:

```javascript
bot.command({
    name: "channelid",
    code: `$send[$channelId[];$channelId[]]`
})
```
