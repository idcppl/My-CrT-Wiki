# LootingLevelEvent

## import
`import crafttweaker.event.LootingLevelEvent;`

## Extended from
[ILivingEvent](/CraftTweaker/Vanilla/Events/ILivingEvent.md) > [IEntityEvent](CraftTweaker/Vanilla/Events/IEntityEvent.md)

## .lootingLevel
> Gets/Sets the level of the looting enchantment.
>
> **Type:** Getter/Setter  
> **Returns:** [int](/CraftTweaker/Vanilla/Base-Types/int.md) 

## .damageSource
> Gets the entity who is attacking with a weapon that has looting enchantment.
>
> **Type:** Getter  
> **Returns:** [IDamageSource](CraftTweaker/Vanilla/Damage/IDamageSource.md)

# By proxy methods

## ILivingEvent
> | Getter/Method   | Setter/Method     | Type                                                                         |
> |-----------------|-------------------|------------------------------------------------------------------------------|
> | entityLivingBase|                   | [IEntityLivingBase](/CraftTweaker/Vanilla/Entities/IEntityLivingBase.md)     |

## IEntityEvent
> | Getter/Method   | Setter/Method     | Type                                                               |
> |-----------------|-------------------|--------------------------------------------------------------------|
> | entity          |                   | [IEntity](/CraftTweaker/Vanilla/Entities/IEntity.md)               |