# ItemExpireEvent

## import
`import crafttweaker.event.ItemExpireEvent;`

## Extended from
[IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable .md) / IEntityEvent

## .item
> Gets the item that wants to expire.
>
> **Type:** Getter 
> **Returns:** [IEntity](/CraftTweaker/Vanilla/Entities/IEntity.md)Item

## .extraLife
> Gets/Sets the time left before the item expires.
>
> **Type:** Getter/Setter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base Types/int.md)

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