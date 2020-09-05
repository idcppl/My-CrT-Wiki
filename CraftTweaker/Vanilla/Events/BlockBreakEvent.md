# BlockBreakEvent

## import
`import crafttweaker.event.BlockBreakEvent;`

## Extended from
[IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable .md) / IBlockEvent > IEventPositionable

## .isPlayer
> Checks if the block broken by a player.
>
> **Type:** Getter  
> **Returns:** bool

## .player
> Gets the player who broke the block.
>
> **Type:** Getter  
> **Returns:** IPlayer

## .experience
> Gets/Sets the experience dropped from the block.
>
> **Type:** Getter/Setter  
> **Returns:** int 

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
> Makes all blocks drop an experience orb.
>
> ```
> events.onBlockBreak(function(event as BlockBreakEvent) {
>	if(event.isPlayer) {
>		event.experience = 1;
>	}
> });