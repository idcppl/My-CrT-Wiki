# LivingExperienceDropEvent

## import
`import crafttweaker.event.LivingExperienceDropEvent;`

## Extended from
[IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable.md) / [ILivingEvent](/CraftTweaker/Vanilla/Events/ILivingEvent.md) > IEntityEvent

## .droppedExperience
> Gets/Sets the experience of an entity.
>
> **Type:** Getter/Setter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base-Types/int.md)

## .player
> Gets the player who killed the entity.
>
> **Type:** Getter  
> **Returns:** [IPlayer](/CraftTweaker/Vanilla/Player/IPlayer.md)

## .originalExperience
> Gets the original amount of experience dropped by that entity.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base-Types/int.md)

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