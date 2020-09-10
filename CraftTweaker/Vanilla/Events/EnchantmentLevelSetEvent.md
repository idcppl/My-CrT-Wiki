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
> **Returns:** [int](/CraftTweaker/Vanilla/Base-Types/int.md)

## .power
> Gets the power of the enchantment.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base-Types/int.md)

## .item
> Gets the item that being enchanted.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Items/IItemStack.md)

## .originalLevel
> Gets the original Level of the enchantment.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base-Types/int.md)

## .level
> Gets/Sets the level's used in the enchantment.
>
> **Type:** Getter/Setter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base-Types/int.md)

# By proxy methods

## IEventPositionable
> | Getter/Method   | Setter/Method     | Type                                                             |
> |-----------------|-------------------|------------------------------------------------------------------|
> | position        |                   | [IBlockPos](/CraftTweaker/Vanilla/World/IBlockPos.md)            |
> | x               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                   |
> | y               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                   |
> | z               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                   |