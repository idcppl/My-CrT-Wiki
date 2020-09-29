# BlockBreakEvent

## import
`import crafttweaker.event.BlockBreakEvent;`

## Call event
> `events.onBlockBreak`

## Extended from
[IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable.md) / [IBlockEvent](/CraftTweaker/Vanilla/Events/IBlockEvent.md) > [IEventPositionable](/CraftTweaker/Vanilla/Events/IEventPositionable.md)

## .isPlayer
> Checks if the block broken by a player.
>
> **Type:** Getter  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)

## .player
> Gets the player who broke the block.
>
> **Type:** Getter  
> **Returns:** [IPlayer](/CraftTweaker/Vanilla/Player/IPlayer.md)

## .experience
> Gets/Sets the experience dropped from the block.
>
> **Type:** Getter/Setter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base-Types/int.md) 

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
> | Getter/Method   | Setter/Method     | Type                                                  |
> |-----------------|-------------------|-------------------------------------------------------|
> | position        |                   | [IBlockPos](/CraftTweaker/Vanilla/World/IBlockPos.md) |
> | x               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)        |
> | y               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)        |
> | z               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)        |

# Example
> Makes all blocks drop an experience orb.
>
> ```
> events.onBlockBreak(function(event as BlockBreakEvent) {
>	if(event.isPlayer) {
>		event.experience = 1;
>	}
> });
> ```