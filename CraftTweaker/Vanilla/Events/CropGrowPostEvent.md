# CropGrowPostEvent

## import
`import crafttweaker.event.CropGrowPostEvent;`

## Extended from
IBlockEvent > IEventPositionable

## .originalBlockState
> Gets the original block state of the crop.
>
> **Type:** Getter
> **Returns:** IBlockState

## .originalBlock
> Gets the original block of the crop.
>
> **Type:** Getter
> **Returns:** IBlock

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