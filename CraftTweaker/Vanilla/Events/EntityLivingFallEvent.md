# EntityLivingFallEvent

## import
`import crafttweaker.event.EntityLivingFallEvent;`

## Extended from
IEventCancelable / ILivingEvent > IEntityEvent

## .distance
> Gets/Sets the distance the entity has fallen.
>
> **Type:** Getter/Setter  
> **Returns:** float

## .damageMultiplier
> Gets/Sets the damage multiplier for falling.
>
> **Type:** Getter/Setter  
> **Returns:** float

# By proxy methods

## IEventCancelable
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | canceled        | canceled          | bool                  |
> | cencel()        |                   | void                  |

## ILivingEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | entityLivingBase|                   | IEntityLivingBase     |

## IEntityEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | entity          |                   | IEntity               |