# ItemFishedEvent

## import
`import crafttweaker.event.ItemFishedEvent;`

## Extended from

[IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable.md) / [IPlayerEvent](/CraftTweaker/Vanilla/Events/IPlayerEvent.md) > [ILivingEvent](/CraftTweaker/Vanilla/Events/ILivingEvent.md) > [IEntityEvent](CraftTweaker/Vanilla/Events/IEntityEvent.md)

## .damage
> Gets how damage the fishing rod is.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base-Types/int.md)

## .additionalDamage
> Sets the damage done to the fishing rod.
>
> **Type:** Setter  
> **Set to:** [int](/CraftTweaker/Vanilla/Base-Types/int.md)

## .drops
> Gets the potential drops?
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Items/IItemStack.md)[]

# By proxy methods

## IEventCancelable
> | Getter/Method   | Setter/Method     | Type                                                              |
> |-----------------|-------------------|-------------------------------------------------------------------|
> | canceled        | canceled          | [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)                  |
> | cencel()        |                   | [void](/CraftTweaker/Vanilla/Base-Types/void.md)                  |

## IPlayerEvent
> | Getter/Method   | Setter/Method     | Type                                                             |
> |-----------------|-------------------|------------------------------------------------------------------|
> | player          |                   | [IPlayer](/CraftTweaker/Vanilla/Player/IPlayer.md)               |

## ILivingEvent
> | Getter/Method   | Setter/Method     | Type                                                                         |
> |-----------------|-------------------|------------------------------------------------------------------------------|
> | entityLivingBase|                   | [IEntityLivingBase](/CraftTweaker/Vanilla/Entities/IEntityLivingBase.md)     |

## IEntityEvent
> | Getter/Method   | Setter/Method     | Type                                                               |
> |-----------------|-------------------|--------------------------------------------------------------------|
> | entity          |                   | [IEntity](/CraftTweaker/Vanilla/Entities/IEntity.md)               |