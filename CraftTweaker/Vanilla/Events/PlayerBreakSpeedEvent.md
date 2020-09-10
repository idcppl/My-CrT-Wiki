# PlayerBreakSpeedEvent

## import
`import crafttweaker.event.PlayerBreakSpeedEvent;`

## Extended from
[IEventCancelable](CraftTweaker/Vanilla/Events/IEventCancelable.md) / [IEventPositionable](CraftTweaker/Vanilla/Events/IEventPositionable.md) / [IPlayerEvent](CraftTweaker/Vanilla/Events/IPlayerEvent.md) > [ILivingEvent](CraftTweaker/Vanilla/Events/ILivingEvent.md) > [IEntityEvent](CraftTweaker/Vanilla/Events/IEntityEvent.md)

## .blockState
> Gets the block state.
>
> **Type:** Getter  
> **Returns:** [IBlockState](/CraftTweaker/Vanilla/Blocks/IBlockState.md)

## .block
> Gets the block.
>
> **Type:** Getter  
> **Returns:** [IBlock](/CraftTweaker/Vanilla/Blocks/IBlock.md)

## .originalSpeed
> Gets the original breaking speed.
>
> **Type:** Getter  
> **Returns:** [float](/CraftTweaker/Vanilla/Base-Types/float.md)

## .newSpeed
> Gets/Sets the breaking speed.
>
> **Type:** Getter/Setter  
> **Returns:** [float](/CraftTweaker/Vanilla/Base-Types/float.md)

# By proxy methods

## IEventCancelable
> | Getter/Method   | Setter/Method     | Type                                              |
> |-----------------|-------------------|---------------------------------------------------|
> | canceled        | canceled          | [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)  |
> | cencel()        |                   | [void](/CraftTweaker/Vanilla/Base-Types/void.md)  |

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