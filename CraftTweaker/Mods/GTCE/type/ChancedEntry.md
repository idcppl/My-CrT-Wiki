# ChancedEntry
ChancedEntry is an item output that has a chance of being outputted. The formula used for calculating the chance is `chance + (boostPerTier * tier)`

## import
`import mods.gregtech.recipe.ChancedEntry;`

# .output
>Holds the output item.
>
>**Returns:** IItemStack 

# .chance
>Holds the initial chance for the output item.
>
>**Returns:** int

# .boostPerTier
>Holds the boosted chance of getting an output item based on tiers.
>
>**Returns:** int