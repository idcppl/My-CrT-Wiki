# BlockPlaceEvent

## import
`import crafttweaker.event.BlockPlaceEvent;`

## Extended from
IEventCancelable / IBlockEvent > IEventPositionable

## .player
> Gets the player who placed the block.
>
> **Type:** Getter  
> **Returns:** IPlayer

## .current
> Gets the blockstate of the block that is being placed.
>
> **Type:** Getter  
> **Returns:** IBlockState

## .placedAgainst
> Gets the blockstate of the block that you're placing against.
>
> **Type:** Getter  
> **Returns:** IBlockState

## .hand
> Gets the block in the player hand.
>
> **Type:** Getter  
> **Returns:** string

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