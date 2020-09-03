# Machines
GTCE stores all it's recipes in a `RecipeMap`

## Imports
`import mods.gregtech.recipe.RecipeMap;`

# Methods to retrieve RecipeMaps
> | Method Call                           | Returns       |
> |---------------------------------------|---------------|
> | getRecipeMaps()                       | RecipeMap[]   |
> | getByName(string unlocalizedName)     | RecipeMap     |
>
>### Retrieving RecipeMaps notes
>- `getByName()` uses an unlocalized name from the machines below.
>- `getRecipeMaps()` returns all crafting machines RecipeMap.

## List of machines and their requirements
| Unlocalized Name          | Input Amount  | Output Amount | Fluid Input Amount    | Fluid Output Amount   | Property  |
|---------------------------|---------------|---------------|-----------------------|-----------------------|-----------|
|compressor                 |1              |1              |0                      |0                      | none      |
|extractor                  |1              |1              |0                      |0                      | none      |
|macerator                  |1              |1-3            |0                      |0                      | none      |
|orewasher                  |1              |1-3            |0-1                    |0                      | none      |
|thermal_centrifuge         |1              |1-3            |0                      |0                      | none      |
|furnace                    |1              |1              |0                      |0                      | none      |
|microwave                  |1              |1              |0                      |0                      | none      |
|assembler                  |1-9            |1              |0-1                    |0                      | circuit   |
|forming_press              |2-6            |1              |0                      |0                      | none      |
|fluid_canner               |1              |0-1            |0-1                    |0-1                    | none      |
|plasma_arc_furnace         |1              |1-4            |1                      |0-1                    | none      |
|arc_furnace                |1              |1-4            |1                      |0                      | none      |
|sifter                     |1              |0-6            |0                      |0                      | none      |
|laser_engraver             |2              |1              |0                      |0                      | none      |
|mixer                      |0-4            |0-1            |0-2                    |0-1                    | none      |
|autoclave                  |1              |1              |1                      |0                      | none      |
|electromagnetic_separator  |1              |1-3            |1                      |0                      | none      |
|polarizer                  |1              |1              |0                      |0                      | none      |
|chemical_bath              |1              |1-3            |1                      |0                      | none      |
|brewer                     |1              |0              |1                      |1                      | none      |
|fluid_heater               |1              |0              |1                      |1                      | circuit   |
|distillery                 |1              |0              |1                      |1                      | circuit   |
|fermenter                  |0              |0              |1                      |1                      | none      |
|fluid_solidifier           |1              |1              |1                      |0                      | none      |
|fluid_extractor            |1              |0-1            |0                      |1                      | none      |
|fusion_reactor             |0              |0              |0-2                    |1                      | none      |
|centrifuge                 |0-1            |0-6            |0-1                    |0-6                    | none      |
|electrolyzer               |0-1            |0-6            |0-1                    |0-6                    | none      |
|blast_furnace              |1-3            |1-2            |0-1                    |0-1                    |temperature|
|implosion_compressor       |2-3            |1-2            |0                      |0                      | explosives|
|vacuum_freezer             |0-1            |0-1            |0-1                    |0-1                    | none      |
|chemical_reactor           |0-2            |0-1            |0-3                    |0-2                    | none      |
|distillation_tower         |0              |0-1            |1                      |1-12                   | none      |
|cracker                    |0              |0              |2                      |1-2                    | none      |
|pyro                       |2              |0-1            |0-1                    |1                      | circuit   |
|wiremill                   |1              |1              |0                      |0                      | none      |
|metal_bender               |2              |1              |0                      |0                      | circuit   |
|alloy_smelter              |1-2            |1              |0                      |1                      | none      |
|canner                     |1-2            |1-2            |0                      |0                      | none      |
|lathe                      |1              |1-2            |0                      |0                      | none      |
|cutting_saw                |1              |1-2            |0-1                    |0                      | none      |
|extruder                   |2              |1              |0                      |0                      | none      |
|forge_hammer               |1              |1              |0                      |0                      | none      |
|packer                     |2              |1              |0                      |0                      | none      |
|unpacker                   |2              |1-2            |0                      |0                      | none      |

### Machines notes
- `Input/Output/Fluid Input/Fluid Output` Amount is the min to max amount of inputs that can be accepted for that machine.
- Machines without the property `circuit` can still have circuits added to their recipes through `.notConsumable()` method.

## Methods to use on RecipeMaps
| Method Call                                                           | Returns           |
|-----------------------------------------------------------------------|-------------------|
| findRecipe(long EUt, IItemStack[] inputs, ILiquidStack[] fluidInputs) | CTRecipe          |
| recipes                                                               | CTRecipe[]        |
| localizedName                                                         | string            |
| unlocalizedName                                                       | string            |
| recipeBuilder()                                                       | CTRecipeBuilder   |

### RecipeMap notes
- `findRecipe()` the `IItemStack[]` and `ILiquidStack[]` are nullable.

## Methods for CTRecipeBuilder
| Method Calls                                                                  | Count As                      |
|-------------------------------------------------------------------------------|-------------------------------|
| inputs(IIngredient[] ingredients)                                             | Input Amount                  |
| notConsumable(IIngredient ingredient)                                         | Input Amount                  |
| outputs(IItemStack[] ingredients)                                             | Output Amount                 |
| chancedOutput(IItemStack outputStack, int chanceValue, int tierChanceBoost)   | Output Amount                 |
| fluidInputs(ILiquidStack[] ingredients)                                       | Fluid Input Amount            |
| fluidOutputs(ILiquidStack[] ingredients)                                      | Fluid Output Amount           |
| property(string key, IItemStack value)                                        | Can count as Input Amount     |
| property(string key, int value)                                               | Can count as Input Amount     |
| hidden()                                                                      | none                          |
| EUt(int EUt)                                                                  | none                          |
| duration(int duration)                                                        | none                          |
| buildAndRegister()                                                            | none                          |
| toString()                                                                    | none                          |

### CTRecipeBuilder notes
- `chancedOutput()` the `chanceValue` and `tierChanceBoost` are an int between `0-10000`.
- `property()` is counted as an input when it is set to the key of: `circuit` or `explosives`.
- `hidden()` hides the recipe in JEI.

## Property's
| Key Name      | Value as          | Use                                           |
|---------------|-------------------|-----------------------------------------------|
| circuit       | int               | Acts as a none consumable circuit             |
| temperature   | int               | Sets the temperature for the recipe           |
| Explosives    | int               | Acts as the amount of explosives in the input |
| Explosives    | IItemStack        | Sets the IItemStack for the explosives input  |