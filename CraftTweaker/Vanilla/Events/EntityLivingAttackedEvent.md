# EntityLivingAttackedEvent

## import
`import crafttweaker.event.EntityLivingAttackedEvent;`

## Extended from
IEventCancelable / ILivingEvent > IEntityEvent

## .damageSource
> Gets the source of the damage.
>
> **Type:** Getter  
> **Returns:** IDamageSource

## .amount
> Gets the amount of damage about to be done.
>
> **Type:** Getter  
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