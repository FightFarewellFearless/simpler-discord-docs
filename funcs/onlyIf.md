# $onlyIf
execute the funcs above only if the condition is true, else, error message will sended
## usage:
```js
$onlyIf[condition;error message]
```
## example:
```js
$send[$channelId[];Your args 1 is "hi"]
$onlyIf["$message[1]" == "hi";your args 1 isn't "hi"]
```
