# LootingLevelEvent

## import
`import crafttweaker.event.LootingLevelEvent;`

## Extended from
[ILivingEvent](/CraftTweaker/Vanilla/Events/ILivingEvent.md) > IEntityEvent

## .lootingLevel
> Gets/Sets the level of the looting enchantment.
>
> **Type:** Getter/Setter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base Types/int.md) 

## .damageSource
> Gets the entity who is attacking with a weapon that has looting enchantment.
>
> **Type:** Getter  
> **Returns:** IDamageSource

# By proxy methods

## ILivingEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | entityLivingBase|                   | IEntityLivingBase     |

## IEntityEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | entity          |                   | IEntity               |