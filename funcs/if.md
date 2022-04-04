---
description: return message depends on condition
---

# $if

## Usage:

\[condition;message when true;message when false]

## Example:

```js
$send[$channelId[];$if[$message[1]==hi;your args 1 is hi;your args 1 isn't hi]]
```

```
$if[1!=NaN;yes;no]
// will return yes

$if[1<2;yes;no]
// will return yes

$if[1>2;yes;no]
// will return no
```

## Example Command:

```javascript
bot.command({
    name: "if",
    code: `$send[$channelId[];$if[$message[1]==hi;your args 1 is hi;your args 1 isn't hi]]`
})

// if the message in the first args is "hi" it 
// will output the message "your args 1 is hi" 
// otherwise if not "hi" it will output the message
// "your args 1 isn't hi"
```
