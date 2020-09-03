# CropGrowPreEvent

## import
`import crafttweaker.event.CropGrowPreEvent;`

## Extended from
IEventHasResult / IBlockEvent > IEventPositionable

# By proxy methods

## IEventHasResult
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | result          |                   | string                |
> |                 | deny              | void                  |
> |                 | default           | void                  |
> |                 | allow             | void                  |

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