# EntityLivingUseItemEvent

## import
`import crafttweaker.event.EntityLivingUseItemEvent.All;`  
`import crafttweaker.event.EntityLivingUseItemEvent.Start;`  
`import crafttweaker.event.EntityLivingUseItemEvent.Stop;`  
`import crafttweaker.event.EntityLivingUseItemEvent.Finish;`  
`import crafttweaker.event.EntityLivingUseItemEvent.Tick;`

## Extended from
(All) [IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable .md) / [ILivingEvent](/CraftTweaker/Vanilla/Events/ILivingEvent.md) > IEntityEvent  
(Start, Stop, Finish, Tick) EntityLivingUseItemEvent > [IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable .md) / [ILivingEvent](/CraftTweaker/Vanilla/Events/ILivingEvent.md) > IEntityEvent  

## .item
> Gets the item the entity is trying to use.
>
> **Type:** Getter  
> **Returns:** [int](/CraftTweaker/Vanilla/Items/IItemStack.md)

## .isPlayer
> Checks if the entity is a player.
>
> **Type:** Getter  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base Types/bool.md)

## .player
> Gets the player.
>
> **Type:** Getter  
> **Returns:** [IPlayer](/CraftTweaker/Vanilla/Player/IPlayer.md)

## .duration
> Gets/Sets the duration of the item cast time.
>
> **Type:** Getter/Setter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base Types/int.md)

# By proxy methods

## IEventCancelable
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | canceled        | canceled          | bool                  |
> | cencel()        |                   | void                  |

## ILivingEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | entityLivingBase|                   | IEntityLivingBase     |

## IEntityEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | entity          |                   | IEntity               |