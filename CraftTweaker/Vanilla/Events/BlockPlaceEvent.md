# BlockPlaceEvent

## import
`import crafttweaker.event.BlockPlaceEvent;`

## Extended from
[IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable .md) / IBlockEvent > IEventPositionable

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
> **Returns:** [string](/CraftTweaker/Vanilla/Base Types/string.md)

# By proxy methods

## IEventCancelable
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | canceled        | canceled          | bool                  |
> | cencel()        |                   | void                  |

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