---
description: create leaderboard for server var.
---

# $userLeaderboard
Available keyword for text: `{position}` to get server position at the leaderboard

`{name}` server name

`{value}` to get the variable value for the server
## Usage:
[varName;text(optional);list(optional);page(optional)]

## Example:
```
$send[$channelId[];most players leaderboard {createEmbed:{description:$userLeaderboard[player;{position}. {name} | {value}]}}]
```
