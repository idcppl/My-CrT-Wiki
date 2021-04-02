# Material

## import
`import mods.gregtech.material.Material;`

## .color
> Gets the color of the material in decimal.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base-Types/int.md)

## .chemicalFormula
> Gets the chemical formula of the material.
>
> **Type:** Getter  
> **Returns:** [string](/CraftTweaker/Vanilla/Base-Types/string.md)

## .iconSet
> Gets the icon set of the material.
>
> **Type:** Getter  
> **Returns:** [MaterialIconSet](/CraftTweaker/Mods/GTCE/Materials/Types/MaterialIconSet.md)

## .components
> Gets the components of the material.
>
> **Type:** Getter  
> **Returns:** [MaterialStack](/CraftTweaker/Mods/GTCE/Materials/MaterialStack.md)[]

## .generationFlagsRaw
> Should return `0 | 1 | 2 ..`, but it broke.
>
> **Type:** Getter  
> **Returns:** [long](/CraftTweaker/Vanilla/Base-Types/long.md)

## .element
> Gets the element for the material.
>
> **Type:** Getter  
> **Returns:** [Element](/CraftTweaker/Mods/GTCE/Materials/Element.md)

## .hasFlagRaw(flag)
> Checks if the material has the given flag.
>
> **Type:** Method  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)
> | Parameters | Type                                             |
> |------------|--------------------------------------------------|
> | flag       | [long](/CraftTweaker/Vanilla/Base-Types/long.md) |

## addFlags(flags)
> Adds flags to a material. `...` is an array, but doesn't have to be in `[]`.
>
> **Type:** Method  
> | Parameters | Type                                                    |
> |------------|---------------------------------------------------------|
> | flags      | [string](/CraftTweaker/Vanilla/Base-Types/string.md)... |

## .hasFlag(flag)
> Checks if the material has the given flag.
>
> **Type:** Method  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)
> | Parameters | Type                                                 |
> |------------|------------------------------------------------------|
> | flag       | [string](/CraftTweaker/Vanilla/Base-Types/string.md) |

## .radioactive
> Tells you if the material is radioactive. Believe it currently does nothing.
>
> **Type:** Getter  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)

## .protons
> Gets the amount of protons in the material. If the material has no element or components with elements, it is given the stats of `Technetium`. If it does have components the formula is, `MaterialStack.amount * element.protons` added all together.
>
> **Type:** Getter  
> **Returns:** [long](/CraftTweaker/Vanilla/Base-Types/long.md)

## .neutrons
> Gets the amount of neutrons in the material. If the material has no element or components with elements, it is given the stats of `Technetium`.
>
> **Type:** Getter  
> **Returns:** [long](/CraftTweaker/Vanilla/Base-Types/long.md)

## .mass
> Gets the amount of protrons + neutrons. If the material has no element or components with elements, it is given the stats of `Technetium`.
>
> **Type:** Getter  
> **Returns:** [long](/CraftTweaker/Vanilla/Base-Types/long.md)

##
>
>
> **Type:**
> **Returns:**