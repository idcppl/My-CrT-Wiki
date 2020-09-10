# EntityLivingSpawnEvent

## import
`import crafttweaker.event.EntityLivingSpawnEvent;`

## Extended from
[ILivingEvent](/CraftTweaker/Vanilla/Events/ILivingEvent.md) > [IEntityEvent](CraftTweaker/Vanilla/Events/IEntityEvent.md)

## .world
> Gets the world the entity spawned in.
>
> **Type:** Getter  
> **Returns:** [IWorld](/CraftTweaker/Vanilla/World/IWorld.md)

## .x
> Gets the X axis position.
>
> **Type:** Getter  
> **Returns:** [float](/CraftTweaker/Vanilla/Base-Types/float.md)

## .y
> Gets the Y axis position.
>
> **Type:** Getter  
> **Returns:** [float](/CraftTweaker/Vanilla/Base-Types/float.md)

## .z
> Gets the Z axis position.
>
> **Type:** Getter  
> **Returns:** [float](/CraftTweaker/Vanilla/Base-Types/float.md)

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
> | Getter/Method   | Setter/Method     | Type                                                                         |
> |-----------------|-------------------|------------------------------------------------------------------------------|
> | entityLivingBase|                   | [IEntityLivingBase](/CraftTweaker/Vanilla/Entities/IEntityLivingBase.md)     |

## IEntityEvent
> | Getter/Method   | Setter/Method     | Type                                                               |
> |-----------------|-------------------|--------------------------------------------------------------------|
> | entity          |                   | [IEntity](/CraftTweaker/Vanilla/Entities/IEntity.md)               |