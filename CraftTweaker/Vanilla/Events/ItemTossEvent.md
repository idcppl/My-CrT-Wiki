# ItemTossEvent

## import
`import crafttweaker.event.ItemTossEvent;`

## Extended from
[IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable.md) / IEntityEvent

## .player
> Gets the player.
>
> **Type:** Getter  
> **Returns:** [IPlayer](/CraftTweaker/Vanilla/Player/IPlayer.md)

## .item
> Gets the item that is being tossed.
>
> **Type:** Getter 
> **Returns:** [IEntity](/CraftTweaker/Vanilla/Entities/IEntity.md)Item

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