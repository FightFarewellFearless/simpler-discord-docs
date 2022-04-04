---
description: return the value from $let
---

# $get

## Usage:

\[name]

## Example:

```
$get[Foo]
$let[Foo;Bar]
```

## Example Command:

```javascript
bot.command({
    name: "foo",
    code: `$send[$channelId[];$get[Foo]]
    $let[Foo;Bar]`
})
```

### Output:

![](../.gitbook/assets/gambar.png)
