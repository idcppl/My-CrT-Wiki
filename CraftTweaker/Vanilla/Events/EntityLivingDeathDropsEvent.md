# EntityLivingDeathDropsEvent

## import
`import crafttweaker.event.EntityLivingDeathDropsEvent;`

## Extended from
[IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable.md) / [ILivingEvent](/CraftTweaker/Vanilla/Events/ILivingEvent.md) > [IEntityEvent](CraftTweaker/Vanilla/Events/IEntityEvent.md)

## .damageSource
> Gets the damage source that killed the entity.
>
> **Type:** Getter  
> **Returns:** [IDamageSource](CraftTweaker/Vanilla/Damage/IDamageSource.md)

## .addItem(item/entityItem)
>
>
> **Type:** Method  
> | Parameters      | Type                                                            |
> |-----------------|-----------------------------------------------------------------|
> | item            | [IItemStack](/CraftTweaker/Vanilla/Items/IItemStack.md)         |
> | entityItem      | [IEntityItem](/CraftTweaker/Vanilla/Entities/IEntityItem.md)    |

## .lootingLevel
> Gets the looting level of the weapon used.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base-Types/int.md)

## .isRecentlyHit
> Checks if it has been recently hit by a player.
>
> **Type:** Getter  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)

## .drops
> Gets/Sets the drops of the entity.
>
> **Type:** Getter/Setter  
> **Returns:** [IEntityItem](/CraftTweaker/Vanilla/Entities/IEntityItem.md)

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