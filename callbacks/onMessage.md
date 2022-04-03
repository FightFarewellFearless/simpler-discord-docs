# onMessage

trigger command when message sended

## Usage:

```js
<bot>.onMessage()
```

## Command

```js
<bot>.command({
name: "name", //command name
code: `code`
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
