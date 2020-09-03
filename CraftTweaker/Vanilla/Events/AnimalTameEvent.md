# AnimalTameEvent

## import
`import crafttweaker.event.AnimalTameEvent;`

## Extended From

IEventCancable / IPlayerEvent > ILivingEvent > IEntityEvent

## .animal
> Gets the animal that was tamed.
>
> **Type:** Getter  
> **Returns:** IEntityAnimal

## .tamer
> Gets the player.
>
> **Type:** Getter  
> **Returns:** IPlayer

# By proxy methods

## IEventCancable
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