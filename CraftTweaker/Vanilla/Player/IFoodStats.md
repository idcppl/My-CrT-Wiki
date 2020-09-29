# IFoodStats

## import
`import crafttweaker.player.IFoodStats;`

## .addStats(foodValue, saturationLevel)
> Adds to the player food value and saturation level.
>
> **Type:** Method  
> | Parameters      | Type                                               |
> |-----------------|----------------------------------------------------|
> | foodValue       | [int](/CraftTweaker/Vanilla/Base-Types/int.md)     |
> | saturationLevel | [float](/CraftTweaker/Vanilla/Base-Types/float.md) |

## .onUpdate(player)
> idk
>
> **Type:** Method  
> | Parameters | Type                                               |
> |------------|----------------------------------------------------|
> | player     | [IPlayer](/CraftTweaker/Vanilla/Player/IPlayer.md) |

## .asNBT()
> Acts and allows `as IData`.
>
> **Type:** ZenCaster  
> **Returns:** [IData](CraftTweaker/Vanilla/Data/IData.md)

## .foodLevel
> Gets/Sets the food value of the player.
>
> **Type:** Getter/Setter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base-Types/int.md)

## .needFood()
> Tells if the player needs food.
>
> **Type:** Getter  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)

## .addExhaustion(exhaustion)
> Adds something. idk yet.
>
> **Type:** Method  
> | Parameters | Type                                                |
> |------------|-----------------------------------------------------|
> | exhaustion | [float](/CraftTweaker/Vanilla/Base-Types/float.md)  |

## .saturationLevel
> Gets/Sets the player saturation level.
>
> **Type:** Getter/Setter  
> **Returns:** [float](/CraftTweaker/Vanilla/Base-Types/float.md)