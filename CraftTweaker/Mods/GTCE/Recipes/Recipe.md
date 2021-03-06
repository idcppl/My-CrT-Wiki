# Recipe
Recipe is a way to extract data from recipes.

## import
`import mods.gregtech.recipe.Recipe;`

## .inputs
> Gets all the input items in the recipe. Non-consumables will be shown with the amount of 0.
>
> **Type:** Getter  
> **Returns:** [InputIngredient](/CraftTweaker/Mods/GTCE/Recipes/InputIngredient.md)[]

## .outputs
> Gets all the output items that aren't random in the recipe.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Items/IItemStack.md)[]

## .chancedOutputs
> Gets all the random output items in the recipe.
>
> **Type:** Getter  
> **Returns:** [ChancedEntry](/CraftTweaker/Mods/GTCE/Recipes/ChancedEntry.md)[]

## .fluidInputs
> Gets all the fluid inputs in the recipe.
>
> **Type:** Getter  
> **Returns:** [ILiquidStack](CraftTweaker/Vanilla/Liquids/ILiquidStack.md)[]

## .hasInputFluid
> Tells if the recipe holds an [ILiquidStack](CraftTweaker/Vanilla/Liquids/ILiquidStack.md).
>
> **Type:** Method  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)

## .fluidOutputs
> Gets all the fluid outputs in the recipe.
>
> **Type:** Getter  
> **Returns:** [ILiquidStack](CraftTweaker/Vanilla/Liquids/ILiquidStack.md)[]

## .duration
> Gets the duration of the recipe in ticks.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base-Types/int.md)

## .EUt
> Gets the amount of energy used per tick in the recipe.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base-Types/int.md)

## .hidden
> Tells if the recipe is hidden from JEI.
>
> **Type:** Getter  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)

## .propertyKeys
> Tells which property's this recipe holds.
>
> **Type:** Getter  
> **Returns:** [string](/CraftTweaker/Vanilla/Base-Types/string.md)

## .getProperty(key)
> You can do absolutely nothing with this in CraftTweaker. Checkmate Athiest.
>
> **Type:** Method  
> **Returns:** Object
> | Parameters  | Type                                                    |
> |-------------|---------------------------------------------------------|
> | key         | [string](/CraftTweaker/Vanilla/Base-Types/string.md)    |


## .remove()
> Will remove the recipe from the [RecipeMap](/CraftTweaker/Mods/GTCE/Recipes/RecipeMap.md).
>
> **Type:** Method  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)