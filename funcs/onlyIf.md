# $onlyIf
# Usage: [condition;error message(optional)]
# Description: if condition is false it'll stop function execution and return error message

Example: ```js
$send[$channelId[];hi]
$onlyIf[$message[1]==hi;no hi]```