# EntityMountEvent

## import
`import crafttweaker.event.EntityMountEvent`

## Extended from
[IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable.md) / [IEntityEvent](CraftTweaker/Vanilla/Events/IEntityEvent.md)

## .mountingEntity
> Gets the mounting entity.
>
> **Type:** Getter  
> **Returns:** [IEntity](/CraftTweaker/Vanilla/Entities/IEntity.md)

## .mountedEntity
> Gets the mounted entity.
>
> **Type:** Getter  
> **Returns:** [IEntity](/CraftTweaker/Vanilla/Entities/IEntity.md)

## .isMounting
> Checks if an entity is mounting.
>
> **Type:** Getter  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)

## .isDismounting
> Checks if an entity is dismounting
>
> **Type:** Getter  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)

## .world
> Gets the world.
>
> **Type:** Getter  
> **Returns:** [IWorld](/CraftTweaker/Vanilla/World/IWorld.md)

# By proxy methods

## IEventCancelable
> | Getter/Method   | Setter/Method     | Type                                                              |
> |-----------------|-------------------|-------------------------------------------------------------------|
> | canceled        | canceled          | [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)                  |
> | cencel()        |                   | [void](/CraftTweaker/Vanilla/Base-Types/void.md)                  |

## IEntityEvent
> | Getter/Method   | Setter/Method     | Type                                                               |
> |-----------------|-------------------|--------------------------------------------------------------------|
> | entity          |                   | [IEntity](/CraftTweaker/Vanilla/Entities/IEntity.md)               |