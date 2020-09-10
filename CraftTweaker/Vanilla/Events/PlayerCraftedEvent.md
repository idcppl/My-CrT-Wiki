# PlayerCraftedEvent

## import
`import crafttweaker.event.PlayerCraftedEvent;`

## Extended from
[IPlayerEvent](CraftTweaker/Vanilla/Events/IPlayerEvent.md) > [ILivingEvent](CraftTweaker/Vanilla/Events/ILivingEvent.md) > [IEntityEvent](CraftTweaker/Vanilla/Events/IEntityEvent.md)

## .output
> Gets the output item.
>
> **Type:** Getter  
> **Returns:** [IItemStack](/CraftTweaker/Vanilla/Items/IItemStack.md)

## .inventory
> Gets the inventory of the crafting table.
>
> **Type:** Getter  
> **Returns:** [ICraftingInventory](CraftTweaker/Vanilla/Recipes/ICraftingInventory.md)

# By proxy methods

## IPlayerEvent
> | Getter/Method   | Setter/Method     | Type                                                             |
> |-----------------|-------------------|------------------------------------------------------------------|
> | player          |                   | [IPlayer](/CraftTweaker/Vanilla/Player/IPlayer.md)               |

## ILivingEvent
> | Getter/Method   | Setter/Method     | Type                                                                         |
> |-----------------|-------------------|------------------------------------------------------------------------------|
> | entityLivingBase|                   | [IEntityLivingBase](/CraftTweaker/Vanilla/Entities/IEntityLivingBase.md)     |

## IEntityEvent
> | Getter/Method   | Setter/Method     | Type                                                               |
> |-----------------|-------------------|--------------------------------------------------------------------|
> | entity          |                   | [IEntity](/CraftTweaker/Vanilla/Entities/IEntity.md)               |