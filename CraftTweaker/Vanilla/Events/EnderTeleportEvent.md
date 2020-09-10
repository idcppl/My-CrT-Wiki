# EnderTeleportEvent

## import 
`import crafttweaker.event.EnderTeleportEvent;`

## Extended from
[IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable.md) / [ILivingEvent](/CraftTweaker/Vanilla/Events/ILivingEvent.md) > [IEntityEvent](CraftTweaker/Vanilla/Events/IEntityEvent.md)

## .targetX
> Gets/Sets the X position of the enderman/shulker/ender pearl destination.
>
> **Type:** Getter/Setter  
> **Returns:** [double](/CraftTweaker/Vanilla/Base-Types/double.md)

## .targetY
> Gets/Sets the Y position of the enderman/shulker/ender pearl destination.
>
> **Type:** Getter/Setter  
> **Returns:** [double](/CraftTweaker/Vanilla/Base-Types/double.md)

## .targetZ
> Gets/Sets the Z position of the enderman/shulker/ender pearl destination.
>
> **Type:** Getter/Setter  
> **Returns:** [double](/CraftTweaker/Vanilla/Base-Types/double.md)

## .attackDamage
> Gets/Sets the damage taken from throwing an ender pearl.
>
> **Type:** Getter/Setter  
> **Returns:** [float](/CraftTweaker/Vanilla/Base-Types/float.md)

# By proxy methods

## IEventCancelable
> | Getter/Method   | Setter/Method     | Type                                                              |
> |-----------------|-------------------|-------------------------------------------------------------------|
> | canceled        | canceled          | [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)                  |
> | cencel()        |                   | [void](/CraftTweaker/Vanilla/Base-Types/void.md)                  |

## ILivingEvent
> | Getter/Method   | Setter/Method     | Type                                                                         |
> |-----------------|-------------------|------------------------------------------------------------------------------|
> | entityLivingBase|                   | [IEntityLivingBase](/CraftTweaker/Vanilla/Entities/IEntityLivingBase.md)     |

## IEntityEvent
> | Getter/Method   | Setter/Method     | Type                                                               |
> |-----------------|-------------------|--------------------------------------------------------------------|
> | entity          |                   | [IEntity](/CraftTweaker/Vanilla/Entities/IEntity.md)               |