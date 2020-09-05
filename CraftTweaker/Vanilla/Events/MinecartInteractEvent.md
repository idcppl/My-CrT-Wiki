# MinecartInteractEvent

## import
`import crafttweaker.event.MinecartInteractEvent;`

## Extended from
[IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable .md) / IMinecartEvent

## .player
> Gets the player.
>
> **Type:** Getter  
> **Returns:** [IPlayer](/CraftTweaker/Vanilla/Player/IPlayer.md)

## .item
> Gets item in hand.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Items/IItemStack.md)

## .hand
> Gets something.
>
> **Type:** Getter  
> **Returns:** [string](/CraftTweaker/Vanilla/Base Types/string.md)

# By proxy methods

## IEventCancelable
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | canceled        | canceled          | bool                  |
> | cencel()        |                   | void                  |

## IMinecartEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | minecart        |                   | IEntity               |