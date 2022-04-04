---
description: display author avatar, return link of author avatar.
---

# $authorAvatar

## Usage:

\[size(optional);dynamic(optional);format(optional)]

## Example:

```
$authorAvatar[]
```

```
$authorAvatar[2048;no;png]
```

```
$send[$channelId[];$authorAvatar[]]
```

## Example Command:

```javascript
bot.command({
    name: "myavatar",
    code: `$send[$channelId[];$authorAvatar[]]`
})
```
