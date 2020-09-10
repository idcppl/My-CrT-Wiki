# CropGrowPreEvent

## import
`import crafttweaker.event.CropGrowPreEvent;`

## Extended from
[IEventHasResult](/CraftTweaker/Vanilla/Events/IEventHasResult.md) / [IBlockEvent](/CraftTweaker/Vanilla/Events/IBlockEvent.md) > [IEventPositionable](/CraftTweaker/Vanilla/Events/IEventPositionable.md)

# By proxy methods

## IEventHasResult
> | Getter/Method   | Setter/Method     | Type                                                              |
> |-----------------|-------------------|-------------------------------------------------------------------|
> | result          |                   | [string](/CraftTweaker/Vanilla/Base-Types/string.md)              |
> |                 | deny              | [void](/CraftTweaker/Vanilla/Base-Types/void.md)                  |
> |                 | default           | [void](/CraftTweaker/Vanilla/Base-Types/void.md)                  |
> |                 | allow             | [void](/CraftTweaker/Vanilla/Base-Types/void.md)                  |

## IBlockEvent
> | Getter/Method   | Setter/Method     | Type                                                           |
> |-----------------|-------------------|----------------------------------------------------------------|
> | world           |                   | [IWorld](/CraftTweaker/Vanilla/World/IWorld.md)                |
> | blockState      |                   | [IBlockState](/CraftTweaker/Vanilla/Blocks/IBlockState.md)     |
> | block           |                   | [IBlock](/CraftTweaker/Vanilla/Blocks/IBlock.md)               |

## IEventPositionable
> | Getter/Method   | Setter/Method     | Type                                                             |
> |-----------------|-------------------|------------------------------------------------------------------|
> | position        |                   | [IBlockPos](/CraftTweaker/Vanilla/World/IBlockPos.md)            |
> | x               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                   |
> | y               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                   |
> | z               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                   |