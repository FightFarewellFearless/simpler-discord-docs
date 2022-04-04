---
description: eval the function provided in text part
---

# $functionEval

## Usage:

\[text]

## Example:

```js
$send[$channelId[];$functionEval[$message[]]]
```

## Example Command:

```javascript
bot.command({
    name: "e",
    code: `$send[$channelId[];$functionEval[$message[]]]`
})
```

### Preview:

![](../.gitbook/assets/eval.png)

{% hint style="danger" %}
Eval is very sensitive, you should limit the users who want to use eval in your bot or better only you use it.
{% endhint %}
