# BlockFarmlandTrampleEvent

## import
`import crafttweaker.event.BlockFarmlandTrampleEvent;`

## Extended from
[IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable.md) / [IBlockEvent](/CraftTweaker/Vanilla/Events/IBlockEvent.md) > [IEventPositionable](/CraftTweaker/Vanilla/Events/IEventPositionable.md)

## .entity
>
>
> **Type:** Getter  
> **Returns:** [IEntity](/CraftTweaker/Vanilla/Entities/IEntity.md)

## .fallDistance
>
>
> **Type:** Getter  
> **Returns:** [float](/CraftTweaker/Vanilla/Base-Types/float.md)

# By proxy methods

## IEventCancelable
> | Getter/Method   | Setter/Method     | Type                                              |
> |-----------------|-------------------|---------------------------------------------------|
> | canceled        | canceled          | [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)  |
> | cencel()        |                   | [void](/CraftTweaker/Vanilla/Base-Types/void.md)  |

## IBlockEvent
> | Getter/Method   | Setter/Method     | Type                                                          |
> |-----------------|-------------------|---------------------------------------------------------------|
> | world           |                   | [IWorld](/CraftTweaker/Vanilla/World/IWorld.md)               |
> | blockState      |                   | [IBlockState](/CraftTweaker/Vanilla/Blocks/IBlockState.md)    |
> | block           |                   | [IBlock](/CraftTweaker/Vanilla/Blocks/IBlock.md)              |

## IEventPositionable
> | Getter/Method   | Setter/Method     | Type                                                             |
> |-----------------|-------------------|------------------------------------------------------------------|
> | position        |                   | [IBlockPos](/CraftTweaker/Vanilla/World/IBlockPos.md)            |
> | x               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                   |
> | y               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                   |
> | z               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                   |

# Example
> Makes players and animals are not able to trample farmland.
>
> ```
> events.onFarmlandTrample(function(event as BlockFarmlandTrampleEvent) {
>	if(event.entity instanceof IPlayer || event.entity instanceof IEntityAnimal) {
>		event.cancel();
>	}
> });
> ```