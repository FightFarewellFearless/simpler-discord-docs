---
description: make request to provided url
---

# $httpRequest

## Usage:

\[url;property (optional, use this when u want to get json property);method(optional default to get)]

## Example:

```
$httpRequest[https://useless-facts.sameerkumar.website/api]
```

```
$httpRequest[https://useless-facts.sameerkumar.website/api;data;GET]
```

## Example Command:

```javascript
bot.command({
    name: "fact",
    code: `$send[$channelId[];$httpRequest[https://useless-facts.sameerkumar.website/api;data;GET]]
    
```
