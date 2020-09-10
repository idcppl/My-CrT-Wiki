# PlayerPickupXpEvent

## import
`import crafttweaker.event.PlayerPickupXpEvent;`

## Extended from
[IEventCancelable](CraftTweaker/Vanilla/Events/IEventCancelable.md) / [IPlayerEvent](CraftTweaker/Vanilla/Events/IPlayerEvent.md) > [ILivingEvent](CraftTweaker/Vanilla/Events/ILivingEvent.md) > [IEntityEvent](CraftTweaker/Vanilla/Events/IEntityEvent.md)

## .entityXp
> Gets the XP entity.
>
> **Type:** Getter  
> **Returns:** [IEntityXp](/CraftTweaker/Vanilla/Entities/IEntityXp.md)

## .xp
> Gets the XP amount picked up by the player.
>
> **Type:** Getter  
> **Returns:** [float](/CraftTweaker/Vanilla/Base-Types/float.md)

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