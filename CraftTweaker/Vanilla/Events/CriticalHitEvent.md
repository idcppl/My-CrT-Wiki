# CriticalHitEvent

## import
`import crafttweaker.event.CriticalHitEvent;`

## Extended from
[IEventHasResult](/CraftTweaker/Vanilla/Events/IEventHasResult.md) / [IPlayerEvent](/CraftTweaker/Vanilla/Events/IPlayerEvent.md) > [ILivingEvent](/CraftTweaker/Vanilla/Events/ILivingEvent.md) > [IEntityEvent](CraftTweaker/Vanilla/Events/IEntityEvent.md)

## .target
> Gets the target of the critical hit.
>
> **Type:** Getter  
> **Returns:** [IEntity](/CraftTweaker/Vanilla/Entities/IEntity.md)

## .damageModifier
> Gets/Sets the damage modifier for the critical hit.
>
> **Type:** Getter/Setter  
> **Returns:** [float](/CraftTweaker/Vanilla/Base-Types/float.md)

## .oldDamageModifier
> Gets the old damage modifier for the critical hit.
>
> **Type:** Getter  
> **Returns:** [float](/CraftTweaker/Vanilla/Base-Types/float.md)

## .isVanillaCrit
> Checks if the critical hit is from jumping and hitting the target.
>
> **Type:** Getter  
> **Returns:** [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)

# By proxy methods

## IEventHasResult
> | Getter/Method   | Setter/Method     | Type                                                  |
> |-----------------|-------------------|-------------------------------------------------------|
> | result          |                   | [string](/CraftTweaker/Vanilla/Base-Types/string.md)  |
> |                 | deny              | [void](/CraftTweaker/Vanilla/Base-Types/void.md)      |
> |                 | default           | [void](/CraftTweaker/Vanilla/Base-Types/void.md)      |
> |                 | allow             | [void](/CraftTweaker/Vanilla/Base-Types/void.md)      |

## IPlayerEvent
> | Getter/Method   | Setter/Method     | Type                                                  |
> |-----------------|-------------------|-------------------------------------------------------|
> | player          |                   | [IPlayer](/CraftTweaker/Vanilla/Player/IPlayer.md)    |

## ILivingEvent
> | Getter/Method   | Setter/Method     | Type                                                                      |
> |-----------------|-------------------|---------------------------------------------------------------------------|
> | entityLivingBase|                   | [IEntityLivingBase](/CraftTweaker/Vanilla/Entities/IEntityLivingBase.md)  |

## IEntityEvent
> | Getter/Method   | Setter/Method     | Type                                                  |
> |-----------------|-------------------|-------------------------------------------------------|
> | entity          |                   | [IEntity](/CraftTweaker/Vanilla/Entities/IEntity.md)  |