# EntityLivingDeathDropsEvent

## import
`import crafttweaker.event.EntityLivingDeathDropsEvent;`

## Extended from
IEventCancelable / ILivingEvent > IEntityEvent

## .damageSource
> Gets the damage source that killed the entity.
>
> **Type:** Getter  
> **Returns:** IDamageSource

## .addItem(item/entityItem)
>
>
> **Type:** Method  
> | Parameters      | Type          |
> |-----------------|---------------|
> | item            | IItemStack    |
> | entityItem      | IEnityItem    |

## .lootingLevel
> Gets the looting level of the weapon used.
>
> **Type:** Getter  
> **Returns:** int

## .isRecentlyHit
> Checks if it has been recently hit by a player.
>
> **Type:** Getter  
> **Returns:** bool

## .drops
> Gets/Sets the drops of the entity.
>
> **Type:** Getter/Setter  
> **Returns:** IEntityItem

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