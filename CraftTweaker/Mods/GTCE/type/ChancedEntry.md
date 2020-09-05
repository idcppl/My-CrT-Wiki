# ChancedEntry
ChancedEntry is an item output that has a chance of being outputted. The formula used for calculating the chance is `chance + (boostPerTier * tier)`

## import
`import mods.gregtech.recipe.ChancedEntry;`

## .output
> Gets the output item.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Items/IItemStack.md) 

## .chance
> Gets the initial chance for the output item.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base Types/int.md)

## .boostPerTier
> Gets the boosted chance of getting an output item based on tiers.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base Types/int.md)