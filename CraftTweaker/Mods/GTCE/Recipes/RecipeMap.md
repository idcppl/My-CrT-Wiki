# RecipeMap
RecipeMap's is a powerful tool that is used to store recipes for GTCE. You can add, remove, and extract data from recipes. You'll first need to get a [RecipeMap](/CraftTweaker/Mods/GTCE/Recipes/RecipeMap.md) through the methods: [getRecipeMaps()](/CraftTweaker/Mods/GTCE/Recipes/RecipeMap.md#getrecipemaps) and [getByName()](/CraftTweaker/Mods/GTCE/Recipes/RecipeMap.md#getbynameunlocalizedname).

## .getRecipeMaps()
> Holds all the [RecipeMap](/CraftTweaker/Mods/GTCE/Recipes/RecipeMap.md) within `RecipeMaps`.
>
> **Type:** Method  
> **Returns:** [RecipeMap](/CraftTweaker/Mods/GTCE/Recipes/RecipeMap.md)[]

## .getByName(unlocalizedName)
> Holds a machine `RecipeMap` by using the unlocalized machine name in the method.
>
> **Type:** Method  
> **Returns:** [RecipeMap](/CraftTweaker/Mods/GTCE/Recipes/RecipeMap.md)  
> | Parameters  		| types                                                     |
> |---------------------|-----------------------------------------------------------|
> | unlocalizedName	    | [RecipeMap](/CraftTweaker/Mods/GTCE/Recipes/RecipeMap.md)    |

# Methods to use on a RecipeMap
These methods should be used after you've called one of the above methods.

## .findRecipe(maxVoltage, itemInputs, fluidInputs)
> Finds a recipe that fits the parameters.
>
> **Type:** Method  
> **Returns:** [Recipe](/CraftTweaker/Mods/GTCE/Recipes/Recipe.md)  
> | Parameters          | types                                                             |
> |---------------------|-------------------------------------------------------------------|
> | maxVoltage          | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                    |
> | itemInputs          | [IItemStack](/CraftTweaker/Vanilla/Items/IItemStack.md)[]         |
> | fluidInputs         | [ILiquidStack](CraftTweaker/Vanilla/Liquids/ILiquidStack.md)[]    |

## .recipes
> All the recipes for that [RecipeMap](/CraftTweaker/Mods/GTCE/Recipes/RecipeMap.md).
>
> **Type:** Method  
> **Returns:** [Recipe](/CraftTweaker/Mods/GTCE/Recipes/Recipe.md)[]

## .localizedName
> The localized name of the [RecipeMap](/CraftTweaker/Mods/GTCE/Recipes/RecipeMap.md).
>
> **Type:** Method  
> **Returns:** [string](/CraftTweaker/Vanilla/Base-Types/string.md)

## .unlocalizedName
> The unlocalized name of the [RecipeMap](/CraftTweaker/Mods/GTCE/Recipes/RecipeMap.md).
>
> **Type:** Method  
> **Returns:** [string](/CraftTweaker/Vanilla/Base-Types/string.md)

## .recipeBuilder()
> The method to begin building a recipe.
>
> **Type:** Method  
> **Returns:** [RecipeBuilder](/CraftTweaker/Mods/GTCE/Recipes/RecipeBuilder.md) 
> **Example:**  
> ```RecipeMap.getByName("compressor").recipeBuilder()
>   .inputs(<minecraft:cobblestone> * 2)
>   .outputs(<minecraft:stone>)
>   .duration(8 * 20)
>   .EUt(28)
>   .buildAndRegister();
> ```