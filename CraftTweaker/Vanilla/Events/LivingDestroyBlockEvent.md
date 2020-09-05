# LivingDestroyBlockEvent

## import 
`import crafttweaker.event.LivingDestroyBlockEvent;`

## Extended from
IEventPositionable / [IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable.md) / [ILivingEvent](/CraftTweaker/Vanilla/Events/ILivingEvent.md) > IEntityEvent

## .state
> Gets block state.
>
> **Type:** Getter  
> **Returns:** [IBlockState](/CraftTweaker/Vanilla/Blocks/IBlockState.md)

# By proxy methods

## IEventPositionable
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | position        |                   | IBlockPos             |
> | x               |                   | int                   |
> | y               |                   | int                   |
> | z               |                   | int                   |

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