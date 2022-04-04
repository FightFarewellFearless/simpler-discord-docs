---
description: create leaderboard for users in the provided guild id.
---

# $userLeaderboard
Available keyword for text: `{position}` to get user position at the leaderboard

`{name}` user name

`{tag}` user tag

`{value}` to get the variable value for the user
## Usage:
[varName;text(optional);list(optional);page(optional);guildId(optional)]

## Example:
```
$send[$channelId[];Coin leaderboard {createEmbed:{description:$userLeaderboard[coin;{position}. {name} | {value}]}}]
```
