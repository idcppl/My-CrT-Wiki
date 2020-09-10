# PlayerInteractEntityEvent

## import
`import crafttweaker.event.PlayerInteractEntityEvent;`

## Extended from
[IEventCancelable](CraftTweaker/Vanilla/Events/IEventCancelable.md) / [IPlayerEvent](CraftTweaker/Vanilla/Events/IPlayerEvent.md) > [ILivingEvent](CraftTweaker/Vanilla/Events/ILivingEvent.md) > [IEntityEvent](CraftTweaker/Vanilla/Events/IEntityEvent.md)

## .target
> Gets the entity that the player is trying to interact with.
>
> **Type:** Getter  
> **Returns:** [IEntity](/CraftTweaker/Vanilla/Entities/IEntity.md)

# By proxy methods

## IEventCancelable
> | Getter/Method   | Setter/Method     | Type                                              |
> |-----------------|-------------------|---------------------------------------------------|
> | canceled        | canceled          | [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)  |
> | cencel()        |                   | [void](/CraftTweaker/Vanilla/Base-Types/void.md)  |

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