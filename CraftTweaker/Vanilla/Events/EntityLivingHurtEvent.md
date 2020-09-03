# EntityLivingHurtEvent

## import
`import crafttweaker.event.EntityLivingHurtEvent;`

## Extended from
IEventCancelable / ILivingEvent > IEntityEvent

## .damageSource
> Gets the damage source.
>
> **Type:** Getter  
> **Returns:** IDamageSource

## .amount
> Gets the amount of damage dealt to the entity.
>
> **Type:** Getter  
> **Returns:** float

## .setAmount(amount)
>
>
> **Type:** Setter  
> | Parameters          | Type          |
> |---------------------|---------------|
> | amount              | float         |

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