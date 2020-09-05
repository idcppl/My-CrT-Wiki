# ItemFishedEvent

## import
`import crafttweaker.event.ItemFishedEvent;`

## Extended from

[IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable.md) / [IPlayerEvent](/CraftTweaker/Vanilla/Events/IPlayerEvent.md) > [ILivingEvent](/CraftTweaker/Vanilla/Events/ILivingEvent.md) > IEntityEvent

## .damage
> Gets how damage the fishing rod is.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base-Types/int.md)

## .additionalDamage
> Sets the damage done to the fishing rod.
>
> **Type:** Setter  
> **Set to:** int

## .drops
> Gets the potential drops?
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Items/IItemStack.md)[]

# By proxy methods

## IEventCancelable
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | canceled        | canceled          | bool                  |
> | cencel()        |                   | void                  |

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