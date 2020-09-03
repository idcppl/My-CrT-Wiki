# EntityLivingExtendedSpawnEvent

## import
`import crafttweaker.event.EntityLivingExtendedSpawnEvent`

## Extended from
EntityLivingSpawnEvent > ILivingEvent > IEntityEvent

## .spawner
> Gets the base logic for a spawner.
>
> **Type:** Getter  
> **Returns:** IMobSpawnerBaseLogic

# By proxy methods

## EntityLivingSpawnEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | world           |                   | Iworld                |
> | x               |                   | float                 |
> | y               |                   | float                 |
> | z               |                   | float                 |
> | allow           |                   | void                  |
> | deny            |                   | void                  |
> | pass            |                   | void                  |

## ILivingEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | entityLivingBase|                   | IEntityLivingBase     |

## IEntityEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | entity          |                   | IEntity               |