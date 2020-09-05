# ItemTossEvent

## import
`import crafttweaker.event.ItemTossEvent;`

## Extended from
IEventCancelable / IEntityEvent

## .player
> Gets the player.
>
> **Type:** Getter  
> **Returns:** IPlayer

## .item
> Gets the item that is being tossed.
>
> **Type:** Getter 
> **Returns:** IEntityItem

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