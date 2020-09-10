# CropGrowPostEvent

## import
`import crafttweaker.event.CropGrowPostEvent;`

## Extended from
[IBlockEvent](/CraftTweaker/Vanilla/Events/IBlockEvent.md) > [IEventPositionable](/CraftTweaker/Vanilla/Events/IEventPositionable.md)

## .originalBlockState
> Gets the original block state of the crop.
>
> **Type:** Getter
> **Returns:** [IBlockState](/CraftTweaker/Vanilla/Blocks/IBlockState.md)

## .originalBlock
> Gets the original block of the crop.
>
> **Type:** Getter
> **Returns:** [IBlock](/CraftTweaker/Vanilla/Blocks/IBlock.md)

# By proxy methods

## IBlockEvent
> | Getter/Method   | Setter/Method     | Type                                                          |
> |-----------------|-------------------|---------------------------------------------------------------|
> | world           |                   | [IWorld](/CraftTweaker/Vanilla/World/IWorld.md)               |
> | blockState      |                   | [IBlockState](/CraftTweaker/Vanilla/Blocks/IBlockState.md)    |
> | block           |                   | [IBlock](/CraftTweaker/Vanilla/Blocks/IBlock.md)              |

## IEventPositionable
> | Getter/Method   | Setter/Method     | Type                                                             |
> |-----------------|-------------------|------------------------------------------------------------------|
> | position        |                   | [IBlockPos](/CraftTweaker/Vanilla/World/IBlockPos.md)            |
> | x               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                   |
> | y               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                   |
> | z               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                   |