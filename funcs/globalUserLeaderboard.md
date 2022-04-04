---
description: create leaderboard for global users 
---

# $userLeaderboard
Available keyword for text: `{position}` to get user position at the leaderboard

`{name}` user name

`{tag}` user tag

`{value}` to get the variable value for the user in all server ($setGlobalUserVar)
## Usage:
[varName;text(optional);list(optional);page(optional)]

## Example:
```
$send[$channelId[];Coin leaderboard {createEmbed:{description:$globalUserLeaderboard[coin;{position}. {name} | {value}]}}]
```
