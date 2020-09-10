# ItemExpireEvent

## import
`import crafttweaker.event.ItemExpireEvent;`

## Extended from
[IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable.md) / [IEntityEvent](CraftTweaker/Vanilla/Events/IEntityEvent.md)

## .item
> Gets the item that wants to expire.
>
> **Type:** Getter 
> **Returns:** [IEntityItem](/CraftTweaker/Vanilla/Entities/IEntityItem.md)

## .extraLife
> Gets/Sets the time left before the item expires.
>
> **Type:** Getter/Setter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base-Types/int.md)

# By proxy methods

## IEventCancelable
> | Getter/Method   | Setter/Method     | Type                                                              |
> |-----------------|-------------------|-------------------------------------------------------------------|
> | canceled        | canceled          | [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)                  |
> | cencel()        |                   | [void](/CraftTweaker/Vanilla/Base-Types/void.md)                  |

## IEntityEvent
> | Getter/Method   | Setter/Method     | Type                                                              |
> |-----------------|-------------------|-------------------------------------------------------------------|
> | entity          |                   | [IEntity](/CraftTweaker/Vanilla/Entities/IEntity.md)              |