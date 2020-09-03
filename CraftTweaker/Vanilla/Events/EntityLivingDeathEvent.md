# EntityLivingDeathEvent

## import
`import crafttweaker.event.EntityLivingDeathEvent;`

## Extended from
IEventCancelable / ILivingEvent > IEntityEvent

## .damageSource
> Gets the damage source that killed the entity.
>
> **Type:** Getter  
> **Returns:** IDamageSource

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