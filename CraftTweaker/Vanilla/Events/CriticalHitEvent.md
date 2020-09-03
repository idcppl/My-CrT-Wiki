# CriticalHitEvent

## import
`import crafttweaker.event.CriticalHitEvent;`

## Extended from
IEventHasResult / IPlayerEvent > ILivingEvent > IEntityEvent

## .target
> Gets the target of the critical hit.
>
> **Type:** Getter  
> **Returns:** IEntity

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
> **Returns:** bool

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