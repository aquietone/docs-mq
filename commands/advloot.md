## Syntax

**<span style="color:red">/advloot</span> \[<span style="color:blue">personal/shared</span>\]
\[<span style="color:blue">#(index) or "item name"</span>\] \[<span style="color:blue">window commands</span>\]
\[<span style="color:blue">option</span> *command\]***

|                     |                                                                                                                                      |
|---------------------|--------------------------------------------------------------------------------------------------------------------------------------|
| **Window Commands** | **Descritpion**                                                                                                                      |
| **giveto**          | Gives item to that character IE "/advloot share 1 giveto billybob"                                                                   |
| **leave**           | Leaves the item on the corpse (Note: to unlock the corpse from timer, ALL items related to that corpse must be looted or left on it) |
|                     |                                                                                                                                      |

## Description

Usefor for sending commands to the AdvLoot window (some require you to be the master looter)

## Examples

|                                             |                                                                                                                                  |
|---------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|
| **Command**                                 | **Description**                                                                                                                  |
| **/advloot shared 1 leave**                 | If you are the Master Looter this will cause item 1 on the share loot list to be left on the corpse                              |
| **/advloot shared "spiderling silk" leave** | If you are the Master Looter this will cause the first "spiderling silk" it finds in the shared list to be left on the corpse... |
| **/advloot shared 3 ag**                    | That will select AG on the shared loot list for item 3                                                                           |
| **/advloot shared 1 giveto eqmule 1**       | If you are the Master Looter this will take the item 1 from the Shared list and give it to EQMule                                |
|                                             |                                                                                                                                  |

## See Also

-   [Slash Commands](slash-commands.md)

