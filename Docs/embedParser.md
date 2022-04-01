# Embed Parser
embed parser is use to send embeds in function

## Functions support
-> $send

-> $cooldown

-> $onlyIf

and many more...

# Embeds parser
`{createEmbed:}` to create a new embed

`{title:text:url (optional)}` to set a title

`{description:text}` to set a description

`{author:text:icon url (optional)}` to set a author

`{authorUrl:link}` to set url in author

`{color:color}` to set a color

`{thumbnail:url}` to set a thumbnail

`{field:name:value:inline (yes/no) (optional)}` to set field

`{image:url}` to set image

`{footer:text:url (optional)}` to set footer

## Example
```js
$send[$channelId[];hello {createEmbed:{description:world}}]
```
