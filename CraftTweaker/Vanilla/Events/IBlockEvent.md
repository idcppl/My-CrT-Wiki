# IBlockEvent

## import
`import crafttweaker.event.IBlockEvent;`

## Extended from
[IEventPositionable](CraftTweaker/Vanilla/Events/IEventPositionable.md)

## .world
> Gets the world the block resides in.
>
> **Type:** Getter  
> **Returns:** [IWorld](/CraftTweaker/Vanilla/World/IWorld.md)

## .blockState
> Gets the blockstate of the block
>
> **Type:** Getter  
> **Returns:** [IBlockState](/CraftTweaker/Vanilla/Blocks/IBlockState.md)

## .block
> Gets the block.
>
> **Type:** Getter  
> **Returns:** [IBlock](/CraftTweaker/Vanilla/Blocks/IBlock.md)

# By proxy methods

## IEventPositionable
> | Getter/Method   | Setter/Method     | Type                                                             |
> |-----------------|-------------------|------------------------------------------------------------------|
> | position        |                   | [IBlockPos](/CraftTweaker/Vanilla/World/IBlockPos.md)            |
> | x               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                   |
> | y               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                   |
> | z               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                   |