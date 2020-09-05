# BlockFarmlandTrampleEvent

## import
`import crafttweaker.event.BlockFarmlandTrampleEvent;`

## Extended from
[IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable .md) / IBlockEvent > IEventPositionable

## .entity
>
>
> **Type:** Getter  
> **Returns:** [IEntity](/CraftTweaker/Vanilla/Entities/IEntity.md)

## .fallDistance
>
>
> **Type:** Getter  
> **Returns:** float

# By proxy methods

## IEventCancelable
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | canceled        | canceled          | bool                  |
> | cencel()        |                   | void                  |

## IBlockEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | world           |                   | IWorld                |
> | blockstate      |                   | IBlockState           |
> | block           |                   | IBlock                |

## IEventPositionable
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | position        |                   | IBlockPos             |
> | x               |                   | int                   |
> | y               |                   | int                   |
> | z               |                   | int                   |

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