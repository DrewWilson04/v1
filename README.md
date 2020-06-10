# Hubbot.xyz

## Table of Contents
* <a href="#documentation">Docs</a>
  * <a href="#commands">Commands</a>

# Documentation
## Commands
`[]` = optional arguments<br>
`<>` = required arguments
### Utility
| command   | arguments | description                                             | aliases                                                                          |
|-----------|-----------|---------------------------------------------------------|----------------------------------------------------------------------------------|
| `help`    | `[]`      | Can give you help based off a category or a command     | `h`                                                                              |
| `ping`    | None      | Lets you see the MS delay for the bot and Discord API   | None                                                                             |
| `disable` | `<>`      | Lets admins disable specific commands                   | `disable-command`,`cmd-off`,`command-off`,`disablecommand`,`cmdoff`,`commandoff` |
| `enable`  | `<>`      | Lets admins enable specific commands                    | `enable-command`,`cmd-on`,`command-on`,`enablecommand`,`cmdon`,`commandon`       |
| `eval`    | `<>`      | Lets the bot owner execute javascript                   | None                                                                             |
| `credits` | None      | Shows all the resources used in creating the Hubbot bot | None                                                                             |
| `purge`   | `<>`      | Lets an admin delete mass amounts of messages           | `del`,`delete`                                                                   |
| `servers` | None      | Shows how many active servers I am in                   | None                                                                             |
| `groups`  | None      | Shows an admin what groups are enabled and disables     | `list-groups`,`show-groups`,`listgroups`,`showgroups`                            |
| `load`    | `<>`      | Lets a bot owner load an edited command                 | `load-command`,`loadcommand`                                                     |
| `unload`  | `<>`      | Lets a bot owner unload an edited command               | `unload-command`,`unloadcommand`                                                 |
| `reload`  | `<>`      | Lets a bot owner reload an edited command               | `reload-command`,`reloadcommand`                                                 |

### Currency
| command       | arguments | description                                                                               | aliases         |
|---------------|-----------|-------------------------------------------------------------------------------------------|-----------------|
| `shop`        | `[]`      | Displays all the items for sale and the item of the day                                   | `store`,`emart` |
| `buy`         | `<>`      | Lets you buy the specified item from the store                                            | `purchase`      |
| `balance`     | `[]`      | Shows your balance or the specified users balance                                         | `bal`           |
| `inventory`   | `[]`      | Shows your inventory ex: items you bought from the shop, or another persons inventory     | `inv`           |
| `leaderboard` | `[]`      | Shows the top three earners of all time, day, week, month, or that are currently online   | `leader`,`top`  |


### Configurations
| command       | arguments | description                                                                                     | aliases |
|---------------|-----------|-------------------------------------------------------------------------------------------------|---------|
| `prefix`      | `<>`      | Change the servers prefix                                                                       | None    |
| `roles`       | None      | Allows server owners/admins to assign roles when leveled up                                     | None    |
| `levelamount` | `<>`      | Let's an owner/admin change how many levels there are (set this before using the roles command) | None    |
| `storeconfig` | None      | Let's an owner or admin config the store (price, items, etc. )                                  | None    |
