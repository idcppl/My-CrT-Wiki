# CTRecipeBuilder

## import
`import mods.gregtech.recipe.RecipeBuilder;`

## .duration(duration)
> Is the duration of the recipe in ticks. (There are 20 ticks in a second)
>
> **Type:** Method
> | Parameters  | types     | Uses                      |
> |-------------|-----------|---------------------------|
> | duration    | [int](/CraftTweaker/Vanilla/Base-Types/int.md)       | Time mother fucker        |

## .EUt(EUt)
> Is the amount of eu used per tick. It is suggested to not use a full packet(32/128/512/1024/ect).
>
> **Type:** Method
> | Parameters  | types     | Uses                      |
> |-------------|-----------|---------------------------|
> | EUt         | [int](/CraftTweaker/Vanilla/Base-Types/int.md)       | energy mother fucker      |

## .hidden()
>To hide the recipe from JEI.
>
> **Type:** Method

## .inputs(ingredients)
> Is the input items for the recipe.
>
> **Type:** Method
> | Parameters  | types             | Uses                      |
> |-------------|-------------------|---------------------------|
> | ingredients | IIngredient...    | Item inputs mother fucker |

## .notConsumable(ingredient)
> Is an input item that is not consumed by the recipe.
>
> **Type:** Method
> | Parameters  | types         | Uses                              |
> |-------------|---------------|-----------------------------------|
> | ingredient  | IIngredient   | Don't consume item mother fucker  |

## .outputs(ingredients)
> Is the output items for the recipe.
>
> **Type:** Method
> | Parameters  | types         | Uses                      |
> |-------------|---------------|---------------------------|
> | ingredients | [IItemStack](/CraftTweaker/Vanilla/Items/IItemStack.md)... | Time mother fucker        |

## .chancedOutput(outputStack, chanceValue, tierChanceBoost)
> Is an output item that has a chance of happening. The ints are a number between 0-10000. The formula used for calculating the chance is `chance + (boostPerTier * tier)`
>
> **Type:** Method
> | Parameters      | types         | Uses                                  |
> |-----------------|---------------|---------------------------------------|
> | outputStack     | IItemStack    | Random item mother fucker             |
> | chanceValue     | [int](/CraftTweaker/Vanilla/Base-Types/int.md)           | Initial chance mother fucker          |
> | tierChanceBoost | [int](/CraftTweaker/Vanilla/Base-Types/int.md)           | Boosted chance by tier mother fucker  |

## .fluidInput(ingredients)
> Is a fluid input for the recipe.
>
> **Type:** Method
> | Parameters  | types             | Uses                      |
> |-------------|-------------------|---------------------------|
> | ingredients | ILiquidStack...   | Fluid input mother fucker |

## .fluidOutput(ingredients)
> Is a fluid output for the recipe.
>
> **Type:** Method
> | Parameters  | types             | Uses                          |
> |-------------|-------------------|-------------------------------|
> | ingredients | ILiquidStack...   | Fluid output mother fucker    |

## .property(key, value)
> Is a property for the recipe. It is used for the property's: `circuit`, `temperature`, and `explosives`. For the `explosives` property the value is halved.
>
> **Type:** Method
> | Parameters  | types             | Uses                      |
> |-------------|-------------------|---------------------------|
> | key         | [string](/CraftTweaker/Vanilla/Base-Types/string.md)            | Property mother fucker    |
> | value       | [int](/CraftTweaker/Vanilla/Base-Types/int.md)               | Number mother fucker      |
>
> * * *
>
> Is a property for the recipe. It is used for setting the explosive material for `explosives`.
>
> **Type:** Method
> | Parameters  | types             | Uses                      |
> |-------------|-------------------|---------------------------|
> | key         | [string](/CraftTweaker/Vanilla/Base-Types/string.md)            | Property mother fucker    |
> | value       | [IItemStack](/CraftTweaker/Vanilla/Items/IItemStack.md)        | Item mother fucker        |

## .buildAndRegister()
> Is the the final method for the recipe builder.
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

## I got bored mother fucker