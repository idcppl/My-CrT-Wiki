# MaterialRegistry
MaterialRegistry can be used to either get existing materials or create new materials.

## import
`import mods.gregtech.material.MaterialRegistry;`

## .get(name)
> Gets the material. There also a bracket handler for this, i.e. `<material:iron>`.
>
> **Type:** Method  
> **Returns:** [Material](/CraftTweaker/Mods/GTCE/Materials/Types/Material.md)
> | Parameters | Type                                                 |
> |------------|------------------------------------------------------|
> | name       | [string](/CraftTweaker/Vanilla/Base-Types/string.md) |

## .getAllMaterials()
> Gets all the materials that are registered.
>
> **Type:** Method  
> **Returns:** [Material](/CraftTweaker/Mods/GTCE/Materials/Types/Material.md)[]

## .createFluidMaterial(id, name, color, iconSet, @OP components)
> Creates a FluidMaterial.
>
> **Type:** Method  
> **Returns:** [FluidMaterial](/CraftTweaker/Mods/GTCE/Materials/Types/FluidMaterial.md)
> | Parameters | Type                                                                         |
> |------------|------------------------------------------------------------------------------|
> | id         | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                               |
> | name       | [string](/CraftTweaker/Vanilla/Base-Types/string.md)                         |
> | color      | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                               |
> | iconSet    | [string](/CraftTweaker/Vanilla/Base-Types/string.md)                         |
> | components | [MaterialStack](/CraftTweaker/Mods/GTCE/Materials/MaterialStack.md)[]        |

## .createDustMaterial(id, name, color, iconSet, havestLevel, @OP components)
> Creates a DustMaterial.
>
> **Type:** Method  
> **Returns:** [DustMaterial](/CraftTweaker/Mods/GTCE/Materials/Types/DustMaterial.md)
> | Parameters      | Type                                                                         |
> |-----------------|------------------------------------------------------------------------------|
> | id              | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                               |
> | name            | [string](/CraftTweaker/Vanilla/Base-Types/string.md)                         |
> | color           | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                               |
> | iconSet         | [string](/CraftTweaker/Vanilla/Base-Types/string.md)                         |
> | harvestLevel    | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                               |
> | components      | [MaterialStack](/CraftTweaker/Mods/GTCE/Materials/MaterialStack.md)[]        |

## .createGemMaterial(id, name, iconSet, harvestLevel, @OP components, @OP toolSpeed, @OP attackDamage, @OP toolDurability)
> Creates a GemMaterial.
>
> **Type:** Method  
> **Returns:** [GemMaterial](/CraftTweaker/Mods/GTCE/Materials/Types/GemMaterial.md)
> | Parameters          | Type                                                                         |
> |---------------------|------------------------------------------------------------------------------|
> | id                  | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                               |
> | name                | [string](/CraftTweaker/Vanilla/Base-Types/string.md)                         |
> | color               | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                               |
> | iconSet             | [string](/CraftTweaker/Vanilla/Base-Types/string.md)                         |
> | harvestLevel        | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                               |
> | components          | [MaterialStack](/CraftTweaker/Mods/GTCE/Materials/MaterialStack.md)[]        |
> | toolSpeed           | [float](/CraftTweaker/Vanilla/Base-Types/float.md)                           |
> | attackDamage        | [float](/CraftTweaker/Vanilla/Base-Types/float.md)                           |
> | toolDurability      | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                               |

## .createIngotMaterial(id, name, iconSet, harvestLvl, @OP components, @OP toolSpeed, @OP attackDamage, @OP toolDurability, @OP temperature)
> Creates an IngotMaterial.
>
> **Type:** Method  
> **Returns:** [IngotMaterial](/CraftTweaker/Mods/GTCE/Materials/Types/IngotMaterial.md)
> | Parameters          | Type                                                                          |
> |---------------------|-------------------------------------------------------------------------------|
> | id                  | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                                |
> | name                | [string](/CraftTweaker/Vanilla/Base-Types/string.md)                          |
> | color               | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                                |
> | iconSet             | [string](/CraftTweaker/Vanilla/Base-Types/string.md)                          |
> | harvestLevel        | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                                |
> | components          | [MaterialStack](/CraftTweaker/Mods/GTCE/Materials/MaterialStack.md)[]         |
> | toolSpeed           | [float](/CraftTweaker/Vanilla/Base-Types/float.md)                            |
> | attackDamage        | [float](/CraftTweaker/Vanilla/Base-Types/float.md)                            |
> | toolDurability      | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                                |
> | temperature         | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                                |

# Author Notes
> - `@OP` means optional.