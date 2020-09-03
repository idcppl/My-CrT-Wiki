# BlockFarmlandTrampleEvent

## import
`import crafttweaker.event.BlockFarmlandTrampleEvent;`

## Extended from
IEventCancable / IBlockEvent > IEventPositionable

## .entity
>
>
> **Type:** Getter  
> **Returns:** IEntity

## .fallDistance
>
>
> **Type:** Getter  
> **Returns:** float

# By proxy methods

## IEventCancable
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