# ItemExpireEvent

## import
`import crafttweaker.event.ItemExpireEvent;`

## Extended from
IEventCancelable / IEntityEvent

## .item
> Gets the item that wants to expire.
>
> **Type:** Getter 
> **Returns:** IEntityItem

## .extraLife
> Gets/Sets the time left before the item expires.
>
> **Type:** Getter/Setter  
> **Returns:** int

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