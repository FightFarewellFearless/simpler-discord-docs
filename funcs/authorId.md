---
description: return author id
---

# $authorId

## Usage:

\[]

## Example:

```
$authorId[]
```

```
$send[$channelId[];$authorId[]]
```

## Example Command:

```javascript
bot.command({
    name: "myid",
    code: `$send[$channelId[];$authorId[]]`
})
```
