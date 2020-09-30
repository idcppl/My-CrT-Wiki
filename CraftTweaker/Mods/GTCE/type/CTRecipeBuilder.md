# CTRecipeBuilder

## import
`import mods.gregtech.recipe.RecipeBuilder;`

## .duration(duration)
> Is the duration of the recipe in ticks. (There are 20 ticks in a second)
>
> **Type:** Method
> | Parameters  | types                                                |
> |-------------|------------------------------------------------------|
> | duration    | [int](/CraftTweaker/Vanilla/Base-Types/int.md)       |

## .EUt(EUt)
> Is the amount of eu used per tick. It is suggested to not use a full packet(32/128/512/1024/ect).
>
> **Type:** Method
> | Parameters  | types                                                |
> |-------------|------------------------------------------------------|
> | EUt         | [int](/CraftTweaker/Vanilla/Base-Types/int.md)       |

## .hidden()
>To hide the recipe from JEI.
>
> **Type:** Method

## .inputs(ingredients)
> Is the input items for the recipe.
>
> **Type:** Method
> | Parameters  | types             |
> |-------------|-------------------|
> | ingredients | IIngredient...    |

## .notConsumable(ingredient)
> Is an input item that is not consumed by the recipe.
>
> **Type:** Method
> | Parameters  | types         |
> |-------------|---------------|
> | ingredient  | IIngredient   |

## .outputs(ingredients)
> Is the output items for the recipe.
>
> **Type:** Method
> | Parameters  | types         |
> |-------------|---------------|
> | ingredients | [IItemStack](/CraftTweaker/Vanilla/Items/IItemStack.md)... |

## .chancedOutput(outputStack, chanceValue, tierChanceBoost)
> Is an output item that has a chance of happening. The ints are a number between 0-10000. The formula used for calculating the chance is `chance + (boostPerTier * tier)`
>
> **Type:** Method
> | Parameters      | types         |
> |-----------------|---------------|
> | outputStack     | IItemStack    |
> | chanceValue     | [int](/CraftTweaker/Vanilla/Base-Types/int.md)           |
> | tierChanceBoost | [int](/CraftTweaker/Vanilla/Base-Types/int.md)           |

## .fluidInput(ingredients)
> Is a fluid input for the recipe.
>
> **Type:** Method
> | Parameters  | types             |
> |-------------|-------------------|
> | ingredients | ILiquidStack...   |

## .fluidOutput(ingredients)
> Is a fluid output for the recipe.
>
> **Type:** Method
> | Parameters  | types             |
> |-------------|-------------------|
> | ingredients | ILiquidStack...   |

## .property(key, value)
> Is a property for the recipe. It is used for the property's: `circuit`, `temperature`, and `explosives`. For the `explosives` property the value is halved.
>
> **Type:** Method
> | Parameters  | types             |
> |-------------|-------------------|
> | key         | [string](/CraftTweaker/Vanilla/Base-Types/string.md)            |
> | value       | [int](/CraftTweaker/Vanilla/Base-Types/int.md)               |
>
> * * *
>
> Is a property for the recipe. It is used for setting the explosive material for `explosives`.
>
> **Type:** Method
> | Parameters  | types             |
> |-------------|-------------------|
> | key         | [string](/CraftTweaker/Vanilla/Base-Types/string.md)           |
> | value       | [IItemStack](/CraftTweaker/Vanilla/Items/IItemStack.md)        |

## .buildAndRegister()
> Is the the final method for the recipe builder.
>
> **Type:** Method  
> **Example:**
> ```RecipeMap.getByName("compressor").recipeBuilder()
>   .inputs(<minecraft:cobblestone> * 2)
>   .outputs(<minecraft:stone>)
>   .duration(8 * 20)
>   .EUt(28)
>   .buildAndRegister();
> ```

## .toString()
> Tells you information about the recipe. Even tells you if the recipe is valid. Can be helpful if having issues.
>
> **Type:** Method  
> **Returns:** [string](/CraftTweaker/Vanilla/Base-Types/string.md)

