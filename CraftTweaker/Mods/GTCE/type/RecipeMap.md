# RecipeMap
RecipeMap's is a powerful tool that is used to store recipes for GTCE. You can add, remove, and extract data from recipes.

# .getRecipeMaps()
> Holds all the `RecipeMap` within `RecipeMaps`.
>
> **Returns:** RecipeMap[]

# .getByName(unlocalizedName)
> Holds a machine `RecipeMap` by using the unlocalized machine name in the method.
>
> **Returns:** RecipeMap
> | Parameters  		| types     | Uses                      |
> |---------------------|-----------|---------------------------|
> | unlocalizedName	    | RecipeMap | For creating recipes		|

# Methods to use on a RecipeMap
These methods should be used after you've called one of the above methods.

# .findRecipe(maxVoltage, itemInputs, fluidInputs)
> Finds a recipe that fits the parameters.
>
> **Returns:** CTRecipe
> | Parameters          | types         | Uses                                  |
> |---------------------|---------------|---------------------------------------|
> | maxVoltage          | int           | a voltage above the recipe required.  |
> | itemInputs          | IItemStack[]  | Nullable. Item inputs.                |
> | fluidInputs         | ILiquidStack[]| Nullable. fluid inputs.               |

# .recipes
> All the recipes for that `RecipeMap`.
>
> **Returns:** CTRecipe[]

# .localizedName
> The localized name of the `RecipeMap`.
>
> **Returns:** string

# .unlocalizedName
> The unlocalized name of the `RecipeMap`.
>
> **Returns:** string

# .recipeBuilder()
> The method to begin building a recipe.
>
> **Returns:** CTRecipeBuilder  
> **Example:**
> ```RecipeMap.getByName("compressor").recipeBuilder()
>   .inputs(<minecraft:cobblestone> * 2)
>   .outputs(<minecraft:stone>)
>   .duration(8 * 20)
>   .EUt(28)
>   .buildAndRegister();
> ```