# $if
## Usage:
 [condition;message when true;message when false]
## Description:
 return message depends on condition

Example: ```js
$send[$channelId[];$if[$message[1]==hi;your args 1 is hi;your args 1 isn't hi]]```