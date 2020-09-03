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
> **Returns:** IItemStack[]

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
> **Returns:** bool

## .fluidOutputs
> Gets all the fluid outputs in the recipe.
>
> **Type:** Getter  
> **Returns:** ILiquidStack[]

## .duration
> Gets the duration of the recipe in ticks.
>
> **Type:** Getter  
> **Returns:** int

## .EUt
> Gets the amount of energy used per tick in the recipe.
>
> **Type:** Getter  
> **Returns:** int

## .hidden
> Tells if the recipe is hidden from JEI.
>
> **Type:** Getter  
> **Returns:** bool

## .propertyKeys
> Tells which property's this recipe holds.
>
> **Type:** Getter  
> **Returns:** string

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
> **Returns:** bool