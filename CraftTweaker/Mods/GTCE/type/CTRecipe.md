# CTRecipe

## import
`import mods.gregtech.recipe.Recipe`

## .inputs
> Gets all the input items in the recipe. Non-consumables will be shown with the amount of 0.
>
> **Type:** Getter  
> **Returns:** [InputIngredient](/CraftTweaker/Mods/GTCE/type/InputIngredient.md)[]

## .outputs
> Gets all the output items that aren't random in the recipe.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Items/IItemStack.md)[]

## .chancedOutputs
> Gets all the random output items in the recipe.
>
> **Type:** Getter  
> **Returns:** [ChancedEntry](/CraftTweaker/Mods/GTCE/type/ChancedEntry.md)[]

## .fluidInputs
> Gets all the fluid inputs in the recipe.
>
> **Type:** Getter  
> **Returns:** ILiquidStack[]

## .hasInputFluid
> Tells if the recipe holds an `ILiquidStack`.
>
> **Type:** Method  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base Types/bool.md)

## .fluidOutputs
> Gets all the fluid outputs in the recipe.
>
> **Type:** Getter  
> **Returns:** ILiquidStack[]

## .duration
> Gets the duration of the recipe in ticks.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base Types/int.md)

## .EUt
> Gets the amount of energy used per tick in the recipe.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base Types/int.md)

## .hidden
> Tells if the recipe is hidden from JEI.
>
> **Type:** Getter  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base Types/bool.md)

## .propertyKeys
> Tells which property's this recipe holds.
>
> **Type:** Getter  
> **Returns:** [string](/CraftTweaker/Vanilla/Base Types/string.md)

## .getProperty(key)
> You can do absolutely nothing with this in CraftTweaker. Checkmate Athiest.
>
> **Type:** Method  
> **Returns:** Object
> | Parameters  | Type      | Use                   |
> |-------------|-----------|-----------------------|
> | key         | string    | name of the property  |


## .remove()
> Will remove the recipe from the `RecipeMap`.
>
> **Type:** Method  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base Types/bool.md)