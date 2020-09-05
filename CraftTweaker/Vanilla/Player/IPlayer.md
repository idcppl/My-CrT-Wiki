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
> **Returns:** [string](/CraftTweaker/Vanilla/Base Types/string.md)

## .data
> Gets the player data.
>
> **Type:** Getter  
> **Returns:** IData

## .xp
> Gets/Sets the player xp.
>
> **Type:** Getter/Setter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base Types/int.md)

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
> | xp              | int           |

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
> | message            | string        |

## .sendStatusMessage(message, hotbar)
> Does something slightly different.
>
> **Type:** Method
> | Parameters         | Type          |
> |--------------------|---------------|
> | message            | IFormattedText|
> | message            | string        |
> | hotbar             | bool          |

## .hotbarSize
> Gets the amount of items in slots in the hotbar.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base Types/int.md)

## .getHotbarStack(i)
> Gets the items from that slot in the hotbar.
>
> **Type:** Method  
> **Returns:** [int](/CraftTweaker/Vanilla/Items/IItemStack.md)
> | Parameters      | Type          |
> |-----------------|---------------|
> | i               | int           |
