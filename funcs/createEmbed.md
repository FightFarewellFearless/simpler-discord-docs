# $createEmbed
embed builder that can use in $send 

this function will return stringify json of embeds
## usage:
```js
$createEmbed[title;author;description;color;thumbnail;timestamp;footer;url;field name:field value:inline?(yes/no);and so on...]
```
All options can be optional depends on how you use it
## example: 
```js
$send[$channelId[];content;no;$createEmbed[hi;author name;this is embed;GREEN]]
```
