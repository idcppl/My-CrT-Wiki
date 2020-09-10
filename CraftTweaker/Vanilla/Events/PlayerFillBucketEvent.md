# PlayerFillBucketEvent

## import
`import crafttweaker.event.PlayerFillBucketEvent;`

## Extended from
[IEventCancelable](CraftTweaker/Vanilla/Events/IEventCancelable.md) / [IProcessableEvent](CraftTweaker/Vanilla/Events/IProcessableEvent.md) / [IEventPositionable](CraftTweaker/Vanilla/Events/IEventPositionable.md) / [IPlayerEvent](CraftTweaker/Vanilla/Events/IPlayerEvent.md) > [ILivingEvent](CraftTweaker/Vanilla/Events/ILivingEvent.md) > [IEntityEvent](CraftTweaker/Vanilla/Events/IEntityEvent.md)

## .reseult
> Gets/Sets the result for the filled container.
>
> **Type:** Getter/Setter  
> **Returns:** [IItemStack](/CraftTweaker/Vanilla/Items/IItemStack.md)

## .emptyBucket
> Gets the empty container item.
>
> **Type:** Getter  
> **Returns:** [IItemStack](/CraftTweaker/Vanilla/Items/IItemStack.md)

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
> **Returns:** [int](/CraftTweaker/Vanilla/Base-Types/int.md)

## .rayTraceResult
> idk
>
> **Type:** Getter  
> **Returns:** [IRayTraceResult](/CraftTweaker/Vanilla/World/IRayTraceResult.md)

# By proxy methods

## IEventCancelable
> | Getter/Method   | Setter/Method     | Type                                              |
> |-----------------|-------------------|---------------------------------------------------|
> | canceled        | canceled          | [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)  |
> | cencel()        |                   | [void](/CraftTweaker/Vanilla/Base-Types/void.md)  |

## IProcessableEvent
> | Getter/Method   | Setter/Method     | Type                                              |
> |-----------------|-------------------|---------------------------------------------------|
> | process()       |                   | [void](/CraftTweaker/Vanilla/Base-Types/void.md)  |
> | processed       |                   | [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)  |

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