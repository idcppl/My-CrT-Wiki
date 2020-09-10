# BlockPlaceEvent

## import
`import crafttweaker.event.BlockPlaceEvent;`

## Extended from
[IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable.md) / [IBlockEvent](/CraftTweaker/Vanilla/Events/IBlockEvent.md) > [IEventPositionable](/CraftTweaker/Vanilla/Events/IEventPositionable.md)

## .player
> Gets the player who placed the block.
>
> **Type:** Getter  
> **Returns:** [IPlayer](/CraftTweaker/Vanilla/Player/IPlayer.md)

## .current
> Gets the blockstate of the block that is being placed.
>
> **Type:** Getter  
> **Returns:** [IBlockState](/CraftTweaker/Vanilla/Blocks/IBlockState.md)

## .placedAgainst
> Gets the blockstate of the block that you're placing against.
>
> **Type:** Getter  
> **Returns:** [IBlockState](/CraftTweaker/Vanilla/Blocks/IBlockState.md)

## .hand
> Gets the block in the player hand.
>
> **Type:** Getter  
> **Returns:** [string](/CraftTweaker/Vanilla/Base-Types/string.md)

# By proxy methods

## IEventCancelable
> | Getter/Method   | Setter/Method     | Type                                              |
> |-----------------|-------------------|---------------------------------------------------|
> | canceled        | canceled          | [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)  |
> | cencel()        |                   | [void](/CraftTweaker/Vanilla/Base-Types/void.md)  |

## IBlockEvent
> | Getter/Method   | Setter/Method     | Type                                                          |
> |-----------------|-------------------|---------------------------------------------------------------|
> | world           |                   | [IWorld](/CraftTweaker/Vanilla/World/IWorld.md)               |
> | blockState      |                   | [IBlockState](/CraftTweaker/Vanilla/Blocks/IBlockState.md)    |
> | block           |                   | [IBlock](/CraftTweaker/Vanilla/Blocks/IBlock.md)              |

## IEventPositionable
> | Getter/Method   | Setter/Method     | Type                                                  |
> |-----------------|-------------------|-------------------------------------------------------|
> | position        |                   | [IBlockPos](/CraftTweaker/Vanilla/World/IBlockPos.md) |
> | x               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)        |
> | y               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)        |
> | z               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)        |