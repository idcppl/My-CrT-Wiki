# PlayerInteractEvent

## import
`import crafttweaker.event.PlayerInteractEvent;`

## Extended from
[IEventPositionable](CraftTweaker/Vanilla/Events/IEventPositionable.md) / [IPlayerEvent](CraftTweaker/Vanilla/Events/IPlayerEvent.md) > [ILivingEvent](CraftTweaker/Vanilla/Events/ILivingEvent.md) > [IEntityEvent](CraftTweaker/Vanilla/Events/IEntityEvent.md)

## .damageItem(amount)
> Damages the item with this interaction.
>
> **Type:** Method  
> | Parameters | Type |
> |------------|------|
> | amount     | int  |

## .world
> Gets the world.
>
> **Type:** Getter  
> **Returns:** [IWorld](/CraftTweaker/Vanilla/World/IWorld.md)

## .block
> Gets the block.
>
> **Type:** Getter  
> **Returns:** [IBlock](/CraftTweaker/Vanilla/Blocks/IBlock.md)

## .blockState
> Gets the block state.
>
> **Type:** Getter  
> **Returns:** [IBlockState](/CraftTweaker/Vanilla/Blocks/IBlockState.md)

## .dimension
> Gets the dimension ID.
>
> **Type:** Getter  
> **Returns:** int

## .hand
> Gets what's in the players hand.
>
> **Type:** Getter  
> **Returns:** string

## .item
> Gets the held item. 
>
> **Type:** Getter  
> **Returns:** IItemStack

# By proxy methods

## IEventPositionable
> | Getter/Method   | Setter/Method     | Type                                                  |
> |-----------------|-------------------|-------------------------------------------------------|
> | position        |                   | [IBlockPos](/CraftTweaker/Vanilla/World/IBlockPos.md) |
> | x               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)        |
> | y               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)        |
> | z               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)        |

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