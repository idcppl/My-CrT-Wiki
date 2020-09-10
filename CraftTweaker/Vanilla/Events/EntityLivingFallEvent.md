# EntityLivingFallEvent

## import
`import crafttweaker.event.EntityLivingFallEvent;`

## Extended from
[IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable.md) / [ILivingEvent](/CraftTweaker/Vanilla/Events/ILivingEvent.md) > [IEntityEvent](CraftTweaker/Vanilla/Events/IEntityEvent.md)

## .distance
> Gets/Sets the distance the entity has fallen.
>
> **Type:** Getter/Setter  
> **Returns:** [float](/CraftTweaker/Vanilla/Base-Types/float.md)

## .damageMultiplier
> Gets/Sets the damage multiplier for falling.
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