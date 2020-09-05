# EntityLivingSpawnEvent

## import
`import crafttweaker.event.EntityLivingSpawnEvent;`

## Extended from
[ILivingEvent](/CraftTweaker/Vanilla/Events/ILivingEvent.md) > IEntityEvent

## .world
> Gets the world the entity spawned in.
>
> **Type:** Getter  
> **Returns:** IWorld

## .x
> Gets the X axis position.
>
> **Type:** Getter  
> **Returns:** float

## .y
> Gets the Y axis position.
>
> **Type:** Getter  
> **Returns:** float

## .z
> Gets the Z axis position.
>
> **Type:** Getter  
> **Returns:** float

## .allow
> Allows the entity to spawn.
>
> **Type:** Method

## .deny
> Deny the entity of spawning.
>
> **Type:** Method

## .pass
> **Need to figure out**
>
> **Type:** Method

# By proxy methods

## ILivingEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | entityLivingBase|                   | IEntityLivingBase     |

## IEntityEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | entity          |                   | IEntity               |