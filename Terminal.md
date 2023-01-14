# Terminal

### User
username@onyx > 'input'

### Commands
#### Moderation Cmds
````command: kick```` ````string: username```` - Kicks the mentioned player

````command: serverban```` ````string: username```` - Bans the mentioned player from the server

````command: ban```` ````string: username/id```` ````numberValue: time```` - Bans the mentioned player from the game

````command: announce```` ````string: announcement```` ````numberValue: timeShown```` - Shows a prompt with the set text to all players

````command: shutdown```` ````string: reason```` - Closes the server

````command: speed```` ````string: player```` ````numberValue: modified_speed```` - Changes the players speed

````command: updatenameid```` ````string: player```` ````string: text```` - Changes the players name shown on the id

````command: updaterankid```` ````string: player```` ````string: text```` - Changes the players rank shown on the id


#### System Cmds

````command: cmds````  - Lists all terminal commands

````command: lock```` ````string: zone```` ````boolean: status```` - (Un)locks mentioned zone

````command: protocol```` ````string: protocol_name```` ````boolean: status```` - (De)activates mentioned protocol

````command: failsafe```` ````string: failsafe_name```` - Executes mentioned failsafe

````command: clear```` ````variable: specified_log (terminal/chat/door/kill)```` - Clears mentioned logs
