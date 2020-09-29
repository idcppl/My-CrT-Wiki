# IPlayer

## import
`import crafttweaker.player.IPlayer;`

## Extended from
IEntityLivingBase > IEntity > ICommandSender  
IUser > ICommandSender

## .name
> Gets the player name.
>
> **Type:** Getter  
> **Returns:** [string](/CraftTweaker/Vanilla/Base-Types/string.md)

## .data
> Gets the player data.
>
> **Type:** Getter  
> **Returns:** IData

## .xp
> Gets/Sets the player xp.
>
> **Type:** Getter/Setter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base-Types/int.md)

## .data
> Gets the player data.
>
> **Type:** Getter  
> **Returns:** IData

## .removeXP(xp)
> Removes X amount of xp.
>
> **Type:** Method  
> | Parameters      | Type          |
> |-----------------|---------------|
> | xp              | [int](/CraftTweaker/Vanilla/Base-Types/int.md)           |

## .update(data)
> Updates the player data.
>
> **Type:** Method  
> | Parameters      | Type          |
> |-----------------|---------------|
> | data            | IData         |

## .sendChat(message)
> Sends a message to chat through the player.
>
> **Type:** Method
> | Parameters         | Type          |
> |--------------------|---------------|
> | message            | IChatMessage  |
> | message            | [string](/CraftTweaker/Vanilla/Base-Types/string.md)        |

## .sendStatusMessage(message, hotbar)
> Does something slightly different.
>
> **Type:** Method
> | Parameters         | Type          |
> |--------------------|---------------|
> | message            | IFormattedText|
> | message            | [string](/CraftTweaker/Vanilla/Base-Types/string.md)        |
> | hotbar             | [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)          |

## .hotbarSize
> Gets the amount of items in slots in the hotbar.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base-Types/int.md)

## .getHotbarStack(i)
> Gets the items from that slot in the hotbar.
>
> **Type:** Method  
> **Returns:** [int](/CraftTweaker/Vanilla/Items/IItemStack.md)
> | Parameters      | Type          |
> |-----------------|---------------|
> | i               | [int](/CraftTweaker/Vanilla/Base-Types/int.md)           |

## .currentItem
> Gets the current item in the player hand.
>
> **Type:** Getter  
> **Returns:** [IItemStack](/CraftTweaker/Vanilla/Items/IItemStack.md)

## .creative
> Tells if the player in creative.
>
> **Type:** Getter  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)

## .adventure
> Tells if the player in adventure.
>
> **Type:** Getter  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)

## .give(stack)
> Gives the player the item.
>
> **Type:** Method  
> | Parameters | Type                                                       |
> |------------|------------------------------------------------------------|
> | stack      | [IItemStack](/CraftTweaker/Vanilla/Items/IItemStack.md)    |

## .teleport(pos)
> Teleports the player to the position.
>
> **Type:** Method
> | Parameters | Type                                                   |
> |------------|--------------------------------------------------------|
> | pos        | [Position3f](CraftTweaker/Vanilla/Util/Position3f.md)  |

## .changeDimension(id)
> Changes the player to another dimension.
>
> **Type:** Method  
> | Parameters | Type                                           |
> |------------|------------------------------------------------|
> | id         | [int](/CraftTweaker/Vanilla/Base-Types/int.md) |

## .score
> Gets/Sets the player score.
>
> **Type:** Getter/Setter  
> **Returns:** int

## .addScore(amount)
> Adds to the player score.
>
> **Type:** Method
> | Parameters | Type                                           |
> |------------|------------------------------------------------|
> | amount     | [int](/CraftTweaker/Vanilla/Base-Types/int.md) |

## .foodStats
> Gets the player food stats.
>
> **Type:** Getter  
> **Returns:** [IFoodStats](/CraftTweaker/Vanilla/Player/IFoodStats.md)

## .executeCommand(rawCommand)
> Tries to execute the command as the player. OP commands won't work if the player is not OP.
>
> **Type:** Method  
> | Parameters | Type                                                   |
> |------------|--------------------------------------------------------|
> | rawCommand | [string](/CraftTweaker/Vanilla/Base-Types/string.md)   |

## .damageDisabled
> Gets/Sets if the player can deal damage?
>
> **Type:** Getter/Setter  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)

## .canFly
> Gets/Sets if the player can fly.
>
> **Type:** Getter/Setter  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)

## .canEdit
> Gets/Sets if the player can edit something?
>
> **Type:** Getter/Setter  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)