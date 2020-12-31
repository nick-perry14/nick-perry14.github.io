# Admin Mode


## Github
[Github Repo](https://github.com/nick-perry14/esx_adminmode)


## Admin On Duty Mode
This is a simple admin-mode project that allows users of a specific group to change into a special "on duty mode".  This mode automatically:
- Gods the player
- Changes their ESX job to an on-duty version
- Heals the player
- Spawns in an admin vehicle (if specified)
- Changes the player's ped automatically (if specified)


Upon Disabling admin mode, the resource:
- Ungods the player
- Returns their ESX Job back to where it was before
- Removes the admin vehicle (unreliable at the current point)
- Resets the player's ped to the ESX skin (looking to change to last ped to work with EUP)


### Admin Panel (View Credit Below)
- Ability to warn, kick, and ban players
- Warns and Kicks can be executed anonymously
- Bans can be executed offline
- Bans ban ALL identifiers (IP, Steam, Rockstar, Discord, etc)


## Commands
- /accassist \[ID\] - Accepts the assist from the specified player and teleports to them
- /adminmode - Toggles the player into admin mode.
- /assist \[reason\] - Requests assistance from admins
- /ban - Opens Ban Window
- /banlist - Opens Ban List
- /cassist - Cancels your active assist.
- /decassist - Declines the pending assist (the assist will still be open for other admins).
- /finassist - Finished the active assist and teleports the admin back to where they were.
- /kick - Opens Kick Window
- /warn - Opens Warn window
- /warnlist - Opens Warn List
- /sc \[message\] - Staff Chat 