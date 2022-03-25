# $if
make a if condition, if true return true message, else it'll return false message

⚠️ Important:

this package is read the function from bottom to top, so function inside function will work, so, if u put function inside $if true/false message, it'll execute earlier than the $if itself, for example if u put $send[] inside $if in false message, then u use $if and it become true, the $send[] will still execute.
## usage:
```js
$if[condition;when true;when false]
```
## example:
```js
$send[$channelId[];$if[$message[1]==hi;your first args is hi;your first args isn't hi]]
```
