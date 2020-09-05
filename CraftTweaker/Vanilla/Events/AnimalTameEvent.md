# AnimalTameEvent

## import
`import crafttweaker.event.AnimalTameEvent;`

## Extended from

[IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable .md) / [IPlayerEvent](/CraftTweaker/Vanilla/Events/IPlayerEvent.md) > [ILivingEvent](/CraftTweaker/Vanilla/Events/ILivingEvent.md) > [IEntityEvent](CraftTweaker/Vanilla/Events/IEntityEvent.md)

## .animal
> Gets the animal that was tamed.
>
> **Type:** Getter  
> **Returns:** [IEntity](/CraftTweaker/Vanilla/Entities/IEntity.md)Animal

## .tamer
> Gets the player.
>
> **Type:** Getter  
> **Returns:** [IPlayer](/CraftTweaker/Vanilla/Player/IPlayer.md)

# By proxy methods

## IEventCancelable
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | canceled        | canceled          | bool                  |
> | cencel()        |                   | void                  |

## IPlayerEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | player          |                   | IPlayer               |

## ILivingEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | entityLivingBase|                   | IEntityLivingBase     |

## IEntityEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | entity          |                   | IEntity               |

# Example
> Names the tamed mob after the player.
>
> ```
> events.onAnimalTame(function(event as AnimalTameEvent) {
>	if !(event.animal.hasCustomName) {
>		var name = event.tamer.name ~ "'s " ~ event.animal.definition.name;
>		event.animal.customName = name;
>	}
> });
> ```