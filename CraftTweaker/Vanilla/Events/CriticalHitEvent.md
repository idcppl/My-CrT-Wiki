# CriticalHitEvent

## import
`import crafttweaker.event.CriticalHitEvent;`

## Extended from
[IEventHasResult](/CraftTweaker/Vanilla/Events/IEventHasResult.md) / [IPlayerEvent](/CraftTweaker/Vanilla/Events/IPlayerEvent.md) > [ILivingEvent](/CraftTweaker/Vanilla/Events/ILivingEvent.md) > [IEntityEvent](CraftTweaker/Vanilla/Events/IEntityEvent.md)

## .target
> Gets the target of the critical hit.
>
> **Type:** Getter  
> **Returns:** [IEntity](/CraftTweaker/Vanilla/Entities/IEntity.md)

## .damageModifier
> Gets/Sets the damage modifier for the critical hit.
>
> **Type:** Getter/Setter  
> **Returns:** float

## .oldDamageModifier
> Gets the old damage modifier for the critical hit.
>
> **Type:** Getter  
> **Returns:** float

## .isVanillaCrit
> Checks if the critical hit is from jumping and hitting the target.
>
> **Type:** Getter  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)

# By proxy methods

## IEventHasResult
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | result          |                   | string                |
> |                 | deny              | void                  |
> |                 | default           | void                  |
> |                 | allow             | void                  |

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