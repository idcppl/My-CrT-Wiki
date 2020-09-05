# PlayerAnvilRepairEvent

## import
`import crafttweaker.event.PlayerAnvilRepairEvent;`

## Extended from
[IPlayerEvent](/CraftTweaker/Vanilla/Events/IPlayerEvent.md) > [ILivingEvent](/CraftTweaker/Vanilla/Events/ILivingEvent.md) > [IEntityEvent](CraftTweaker/Vanilla/Events/IEntityEvent.md)

## .itemResult
> Gets the result.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Items/IItemStack.md)

## .itemIngredient
> Gets first? Second slot?
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Items/IItemStack.md)

## .itemInput
> Gets first? Second slot?
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Items/IItemStack.md)

## .breakChance
> Gets/Sets the break chance?
>
> **Type:** Getter/Setter  
> **Returns:** float

# By proxy methods

## IPlayerEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | player          |                   | IPlayer               |

## ILivingEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | entityLivingBase|                   | IEntityLivingBase     |

## IEntityEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | entity          |                   | IEntity               |