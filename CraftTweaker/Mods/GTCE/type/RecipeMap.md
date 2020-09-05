# RecipeMap
RecipeMap's is a powerful tool that is used to store recipes for GTCE. You can add, remove, and extract data from recipes.

## .getRecipeMaps()
> Holds all the [RecipeMap](/CraftTweaker/Mods/GTCE/type/RecipeMap.md) within `RecipeMaps`.
>
> **Type:** Method  
> **Returns:** [RecipeMap](/CraftTweaker/Mods/GTCE/type/RecipeMap.md)[]

## .getByName(unlocalizedName)
> Holds a machine `RecipeMap` by using the unlocalized machine name in the method.
>
> **Type:** Method  
> **Returns:** [RecipeMap](/CraftTweaker/Mods/GTCE/type/RecipeMap.md)
> | Parameters  		| types                                                     | Uses                      |
> |---------------------|-----------------------------------------------------------|---------------------------|
> | unlocalizedName	    | [RecipeMap](/CraftTweaker/Mods/GTCE/type/RecipeMap.md)    | For creating recipes		|

# Methods to use on a RecipeMap
These methods should be used after you've called one of the above methods.

## .findRecipe(maxVoltage, itemInputs, fluidInputs)
> Finds a recipe that fits the parameters.
>
> **Type:** Method  
> **Returns:** [CTRecipe](/CraftTweaker/Mods/GTCE/type/CTRecipe.md)
> | Parameters          | types         | Uses                                  |
> |---------------------|---------------|---------------------------------------|
> | maxVoltage          | int           | a voltage above the recipe required.  |
> | itemInputs          | IItemStack[]  | Nullable. Item inputs.                |
> | fluidInputs         | ILiquidStack[]| Nullable. fluid inputs.               |

## .recipes
> All the recipes for that [RecipeMap](/CraftTweaker/Mods/GTCE/type/RecipeMap.md).
>
> **Type:** Method  
> **Returns:** [CTRecipe](/CraftTweaker/Mods/GTCE/type/CTRecipe.md)[]

## .localizedName
> The localized name of the [RecipeMap](/CraftTweaker/Mods/GTCE/type/RecipeMap.md).
>
> **Type:** Method  
> **Returns:** [string](/CraftTweaker/Vanilla/Base Types/string.md)

## .unlocalizedName
> The unlocalized name of the [RecipeMap](/CraftTweaker/Mods/GTCE/type/RecipeMap.md).
>
> **Type:** Method  
> **Returns:** [string](/CraftTweaker/Vanilla/Base Types/string.md)

## .recipeBuilder()
> The method to begin building a recipe.
>
> **Type:** Method  
> **Returns:** CTRecipeBuilder  
> **Example:**
> ```RecipeMap.getByName("compressor").recipeBuilder()
>   .inputs(<minecraft:cobblestone> * 2)
>   .outputs(<minecraft:stone>)
>   .duration(8 * 20)
>   .EUt(28)
>   .buildAndRegister();
> ```