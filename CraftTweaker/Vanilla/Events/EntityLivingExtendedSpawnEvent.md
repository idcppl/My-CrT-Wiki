# EntityLivingExtendedSpawnEvent

## import
`import crafttweaker.event.EntityLivingExtendedSpawnEvent`

## Extended from
[EntityLivingSpawnEvent](/CraftTweaker/Vanilla/Events/ILivingEvent.md) > [ILivingEvent](/CraftTweaker/Vanilla/Events/ILivingEvent.md) > [IEntityEvent](CraftTweaker/Vanilla/Events/EntityLivingSpawnEvent.md)

## .spawner
> Gets the base logic for a spawner.
>
> **Type:** Getter  
> **Returns:** [IMobSpawnerBaseLogic](CraftTweaker/Vanilla/TileEntity/IMobSpawnerBaseLogic.md)

# By proxy methods

## EntityLivingSpawnEvent
> | Getter/Method   | Setter/Method     | Type                                                              |
> |-----------------|-------------------|-------------------------------------------------------------------|
> | world           |                   | [IWorld](/CraftTweaker/Vanilla/World/IWorld.md)                   |
> | x               |                   | [float](/CraftTweaker/Vanilla/Base-Types/float.md)                |
> | y               |                   | [float](/CraftTweaker/Vanilla/Base-Types/float.md)                |
> | z               |                   | [float](/CraftTweaker/Vanilla/Base-Types/float.md)                |
> | allow           |                   | [void](/CraftTweaker/Vanilla/Base-Types/void.md)                  |
> | deny            |                   | [void](/CraftTweaker/Vanilla/Base-Types/void.md)                  |
> | pass            |                   | [void](/CraftTweaker/Vanilla/Base-Types/void.md)                  |

## ILivingEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | entityLivingBase|                   | [IEntityLivingBase](/CraftTweaker/Vanilla/Entities/IEntityLivingBase.md)     |

## IEntityEvent
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | entity          |                   | [IEntity](/CraftTweaker/Vanilla/Entities/IEntity.md)               |