# MinecartInteractEvent

## import
`import crafttweaker.event.MinecartInteractEvent;`

## Extended from
ICancelableEvent / IMinecartEvent

## .player
> Gets the player.
>
> **Type:** Getter  
> **Returns:** IPlayer

## .item
> Gets item in hand.
>
> **Type:** Getter  
> **Returns:** IItemStack

## .hand
> Gets something.
>
> **Type:** Getter  
> **Returns:** string

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