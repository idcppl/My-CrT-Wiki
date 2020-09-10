# LivingDestroyBlockEvent

## import 
`import crafttweaker.event.LivingDestroyBlockEvent;`

## Extended from
IEventPositionable / [IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable.md) / [ILivingEvent](/CraftTweaker/Vanilla/Events/ILivingEvent.md) > [IEntityEvent](CraftTweaker/Vanilla/Events/IEntityEvent.md)

## .state
> Gets block state.
>
> **Type:** Getter  
> **Returns:** [IBlockState](/CraftTweaker/Vanilla/Blocks/IBlockState.md)

# By proxy methods

## IEventPositionable
> | Getter/Method   | Setter/Method     | Type                                                             |
> |-----------------|-------------------|------------------------------------------------------------------|
> | position        |                   | [IBlockPos](/CraftTweaker/Vanilla/World/IBlockPos.md)            |
> | x               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                   |
> | y               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                   |
> | z               |                   | [int](/CraftTweaker/Vanilla/Base-Types/int.md)                   |

## IEventCancelable
> | Getter/Method   | Setter/Method     | Type                                                              |
> |-----------------|-------------------|-------------------------------------------------------------------|
> | canceled        | canceled          | [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)                  |
> | cencel()        |                   | [void](/CraftTweaker/Vanilla/Base-Types/void.md)                  |

## ILivingEvent
> | Getter/Method   | Setter/Method     | Type                                                                         |
> |-----------------|-------------------|------------------------------------------------------------------------------|
> | entityLivingBase|                   | [IEntityLivingBase](/CraftTweaker/Vanilla/Entities/IEntityLivingBase.md)     |

## IEntityEvent
> | Getter/Method   | Setter/Method     | Type                                                               |
> |-----------------|-------------------|--------------------------------------------------------------------|
> | entity          |                   | [IEntity](/CraftTweaker/Vanilla/Entities/IEntity.md)               |