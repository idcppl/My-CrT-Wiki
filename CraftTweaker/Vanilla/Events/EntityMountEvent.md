# EntityMountEvent

## import
`import crafttweaker.event.EntityMountEvent`

## Extended from
[IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable .md) / IEntityEvent

## .mountingEntity
> Gets the mounting entity.
>
> **Type:** Getter  
> **Returns:** IEntity

## .mountedEntity
> Gets the mounted entity.
>
> **Type:** Getter  
> **Returns:** IEntity

## .isMounting
> Checks if an entity is mounting.
>
> **Type:** Getter  
> **Returns:** bool

## .isDismounting
> Checks if an entity is dismounting
>
> **Type:** Getter  
> **Returns:** bool

## .world
> Gets the world.
>
> **Type:** Getter  
> **Returns:** IWorld

# By proxy methods

## IEventCancelable
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | canceled        | canceled          | bool                  |
> | cencel()        |                   | void                  |

## IEntityEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | entity          |                   | IEntity               |