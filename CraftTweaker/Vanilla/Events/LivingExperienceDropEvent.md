# LivingExperienceDropEvent

## import
`import crafttweaker.event.LivingExperienceDropEvent;`

## Extended from
IEventCancelable / ILivingEvent > IEntityEvent

## .droppedExperience
> Gets/Sets the experience of an entity.
>
> **Type:** Getter/Setter  
> **Returns:** int

## .player
> Gets the player who killed the entity.
>
> **Type:** Getter  
> **Returns:** IPlayer

## .originalExperience
> Gets the original amount of experience dropped by that entity.
>
> **Type:** Getter  
> **Returns:** int

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