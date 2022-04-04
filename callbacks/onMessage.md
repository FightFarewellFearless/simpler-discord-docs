---
description: trigger command when message sended
---

# onMessage

## Usage:

```js
<bot>.onMessage()
```

## Command

```javascript
<bot>.command({
name: "name", //command name
code: `code`
})
```
or, u can also use "$always" to make command get trigger every time message sended
```javascript
 <bot>.command({
name: "$always",
code: `code`
})
```
### Example:

```js
<bot>.command({
name: "ping",
code: `$send[$channelId[];my websocket ping: $ping[]
my db ping: $pingDb[]]`
})
```

so, when u type `(prefix)ping` it'll send websocket and db ping
