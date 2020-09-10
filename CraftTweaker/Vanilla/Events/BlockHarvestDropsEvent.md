# BlockHarvestDropsEvent

## import
`import crafttweaker.event.BlockHarvestDropsEvent;`

## Extended from
[IBlockEvent](/CraftTweaker/Vanilla/Events/IBlockEvent.md) > [IEventPositionable](/CraftTweaker/Vanilla/Events/IEventPositionable.md)

## .dropChance
> Gets/Sets the drop chance for the block.
>
> **Type:** Getter/Setter  
> **Returns:** [float](/CraftTweaker/Vanilla/Base-Types/float.md)

## .fortuneLevel
> Gets the fortune level for the block.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base-Types/int.md)

## .drops
> Gets/Sets the drops for the block. Has a different set of drops if the tool used has silk touch.
>
> **Type:** Getter/Setter  
> **Returns:** [WeightedItemStack](/CraftTweaker/Vanilla/Items/WeightedItemStack.md)

## .addItem(stack)
> Adds an item to the drops for this block. Will add to a different set depending on if the tool used has silk touch.
>
> **Type:** Method  
> | Parameters      | Type                                                                  |
> |-----------------|-----------------------------------------------------------------------|
> | stack           | [WeightedItemStack](/CraftTweaker/Vanilla/Items/WeightedItemStack.md) |

## .silkTouch
> Checks if the tool used has silk touch. 
>
> **Type:** Getter  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)

## .isPlayer
> Checks if the block is broken by a player.
>
> **Type:** Getter  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)

## .player
> Gets the player who broke the block.
>
> **Type:** Getter  
> **Returns:** [IPlayer](/CraftTweaker/Vanilla/Player/IPlayer.md)

# By proxy methods

## IBlockEvent
> | Getter/Method   | Setter/Method     | Type                                                          |
> |-----------------|-------------------|---------------------------------------------------------------|
> | world           |                   | [IWorld](/CraftTweaker/Vanilla/World/IWorld.md)               |
> | blockstate      |                   | [IBlockState](/CraftTweaker/Vanilla/Blocks/IBlockState.md)    |
> | block           |                   | [IBlock](/CraftTweaker/Vanilla/Blocks/IBlock.md)              |

## IEventPositionable
> | Getter/Method   | Setter/Method     | Type                                                  |
> |-----------------|-------------------|-------------------------------------------------------|
> | position        |                   | [IBlockPos](/CraftTweaker/Vanilla/World/IBlockPos.md) |
> | x               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)        |
> | y               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)        |
> | z               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)        |