# IBlockEvent

## import
`import crafttweaker.event.IBlockEvent;`

## Extended from
IEventPositionable

## .world
> Gets the world the block resides in.
>
> **Type:** Getter  
> **Returns:** IWorld

## .blockState
> Gets the blockstate of the block
>
> **Type:** Getter  
> **Returns:** IBlockState

## .block
> Gets the block.
>
> **Type:** Getter  
> **Returns:** IBlock

# By proxy methods

## IEventPositionable
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | position        |                   | IBlockPos             |
> | x               |                   | int                   |
> | y               |                   | int                   |
> | z               |                   | int                   |