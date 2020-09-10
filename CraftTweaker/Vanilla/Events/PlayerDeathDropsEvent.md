# PlayerDeathDropsEvent

## import
`import crafttweaker.event.PlayerDeathDropsEvent;`

## Extended from
[IPlayerEvent](CraftTweaker/Vanilla/Events/IPlayerEvent.md) > [ILivingEvent](CraftTweaker/Vanilla/Events/ILivingEvent.md) > [IEntityEvent](CraftTweaker/Vanilla/Events/IEntityEvent.md)

## .items
> Gets/Sets the item entities that will drop when the player dies.
>
> **Type:** Getter/Setter  
> **Returns:** [IEntityItem](/CraftTweaker/Vanilla/Entities/IEntityItem.md)[]

## .addItem(item)
> Adds an item to the player drops when they die.
>
> **Type:** Method
> | Parameters | Type                                                           |
> |------------|----------------------------------------------------------------|
> | item       | [IItemStack](/CraftTweaker/Vanilla/Items/IItemStack.md)        |
> | item       | [IEntityItem](/CraftTweaker/Vanilla/Entities/IEntityItem.md)   |

## .damageSource
> Gets the source of damage that killed the player.
>
> **Type:** Getter  
> **Returns:** [IDamageSource](CraftTweaker/Vanilla/Damage/IDamageSource.md)

# By proxy methods

## IPlayerEvent
> | Getter/Method   | Setter/Method     | Type                                                             |
> |-----------------|-------------------|------------------------------------------------------------------|
> | player          |                   | [IPlayer](/CraftTweaker/Vanilla/Player/IPlayer.md)               |

## ILivingEvent
> | Getter/Method   | Setter/Method     | Type                                                                         |
> |-----------------|-------------------|------------------------------------------------------------------------------|
> | entityLivingBase|                   | [IEntityLivingBase](/CraftTweaker/Vanilla/Entities/IEntityLivingBase.md)     |

## IEntityEvent
> | Getter/Method   | Setter/Method     | Type                                                               |
> |-----------------|-------------------|--------------------------------------------------------------------|
> | entity          |                   | [IEntity](/CraftTweaker/Vanilla/Entities/IEntity.md)               |