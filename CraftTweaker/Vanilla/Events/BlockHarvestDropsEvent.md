# BlockHarvestDropsEvent

## import
`import crafttweaker.event.BlockHarvestDropsEvent;`

## Extended from
IBlockEvent > IEventPositionable

## .dropChance
> Gets/Sets the drop chance for the block.
>
> **Type:** Getter/Setter  
> **Returns:** float

## .fortuneLevel
> Gets the fortune level for the block.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base Types/int.md)

## .drops
> Gets/Sets the drops for the block. Has a different set of drops if the tool used has silk touch.
>
> **Type:** Getter/Setter  
> **Returns:** WeightedItemStack

## .addItem(stack)
> Adds an item to the drops for this block. Will add to a different set depending on if the tool used has silk touch.
>
> **Type:** Method  
> | Parameters      | Type              |
> |-----------------|-------------------|
> | stack           | WeightedItemStack |

## .silkTouch
> Checks if the tool used has silk touch. 
>
> **Type:** Getter  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base Types/bool.md)

## .isPlayer
> Checks if the block is broken by a player.
>
> **Type:** Getter  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base Types/bool.md)

## .player
> Gets the player who broke the block.
>
> **Type:** Getter  
> **Returns:** [IPlayer](/CraftTweaker/Vanilla/Player/IPlayer.md)

# By proxy methods

## IBlockEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | world           |                   | IWorld                |
> | blockstate      |                   | IBlockState           |
> | block           |                   | IBlock                |

## IEventPositionable
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | position        |                   | IBlockPos             |
> | x               |                   | int                   |
> | y               |                   | int                   |
> | z               |                   | int                   |