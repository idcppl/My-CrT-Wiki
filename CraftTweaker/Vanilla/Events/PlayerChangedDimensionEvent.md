# PlayerChangedDimensionEvent

## import
`import crafttweaker.event.PlayerChangedDimensionEvent;`

## Extended from
[IPlayerEvent](CraftTweaker/Vanilla/Events/IPlayerEvent.md) > [ILivingEvent](CraftTweaker/Vanilla/Events/ILivingEvent.md) > [IEntityEvent](CraftTweaker/Vanilla/Events/IEntityEvent.md)

## .from
> Gets the dimension the player came from.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base-Types/int.md)

## .to
> Gets the dimension the player is going to.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base-Types/int.md)

## .fromWorld
> Gets the world the player came from.
>
> **Type:** Getter  
> **Returns:** [IWorld](/CraftTweaker/Vanilla/World/IWorld.md)

## .toWorld
> Gets the world the player is going to.
>
> **Type:** Getter  
> **Returns:** [IWorld](/CraftTweaker/Vanilla/World/IWorld.md)

# By proxy methods

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