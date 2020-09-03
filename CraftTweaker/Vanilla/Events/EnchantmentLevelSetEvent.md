# EnchantmentLevelSetEvent

## import
`import crafttweaker.event.EnchantmentLevelSetEvent;`

## Extended from
IEventPositionable

## .world
> Gets the world the enchantment is taking place.
>
> **Type:** Getter  
> **Returns:** IWorld

## .enchantRow
> Gets the row that the enchantment is being called from.
>
> **Type:** Getter  
> **Returns:** int

## .power
> Gets the power of the enchantment.
>
> **Type:** Getter  
> **Returns:** int

## .item
> Gets the item that being enchanted.
>
> **Type:** Getter  
> **Returns:** IItemStack

## .originalLevel
> Gets the original Level of the enchantment.
>
> **Type:** Getter  
> **Returns:** int

## .level
> Gets/Sets the level's used in the enchantment.
>
> **Type:** Getter/Setter  
> **Returns:** int

# By proxy methods

## IEventPositionable
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | position        |                   | IBlockPos             |
> | x               |                   | int                   |
> | y               |                   | int                   |
> | z               |                   | int                   |