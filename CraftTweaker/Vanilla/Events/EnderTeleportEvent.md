# EnderTeleportEvent

## import 
`import crafttweaker.event.EnderTeleportEvent;`

## Extended from
IEventCancelable / ILivingEvent > IEntity

## .targetX
> Gets/Sets the X position of the enderman/shulker/ender pearl destination.
>
> **Type:** Getter/Setter  
> **Returns:** double

## .targetY
> Gets/Sets the Y position of the enderman/shulker/ender pearl destination.
>
> **Type:** Getter/Setter  
> **Returns:** double

## .targetZ
> Gets/Sets the Z position of the enderman/shulker/ender pearl destination.
>
> **Type:** Getter/Setter  
> **Returns:** double

## .attackDamage
> Gets/Sets the damage taken from throwing an ender pearl.
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