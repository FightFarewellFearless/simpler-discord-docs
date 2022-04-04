---
description: edit message with provided message id and channelid
---

# $editMessage

## Usage:

\[messageId;content;channelid (optional)]

## Example:

```
$editMessage[123456;Foo]
```

## Example Command:

```javascript
bot.command({
    name: "edit",
    code: `$editMessage[12345;Foo]`
})

// message will be edited to "Foo"
```
