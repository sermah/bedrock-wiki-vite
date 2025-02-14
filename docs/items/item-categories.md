---
title: Item Categories

nav_order: 3
tags:
    - experimental
---

<Label color="yellow">Experimental</Label>

# Application

Item categories are categories that an item appears in inside of the creative inventory.

## Description 

Item categories applied with the item description direct it to a more broad field in the creative category, individual tabs. They need to be the same tab as the component `creative_category`. Such would be applied like the following example:

```json
{
    "format_version": "1.16.100",
    "minecraft:item": {
        "description": {
            "identifier": "yanasakana:blind_skull",
            "category": "equipment"
        }
    }
}
```



## Component

Item categories applied with the item component `creative_category` direct it exactly where to go. Such would be applied like the following example:

```json
{

    "minecraft:creative_category": {
                "parent": "itemGroup.name.sword"
    }

}
```
> *Note: This feature is currently experimental, and, as such, is currently only available for custom items. Make sure to use the new format!*



# List of Creative Tabs
> *For use with `description` parameter `category`*


| Category                         
| -------------------------------- 
| Commands        |      
| Construction        |      
| Equipment              |      
| Items        |      
| Nature              |      
| None              |      



# List of Item Categories 
> *For use with the `creative_category` component*

| Category                         
| -------------------------------- 
| itemGroup.name.anvil             |      
| itemGroup.name.arrow             |      
| itemGroup.name.axe               |      
| itemGroup.name.banner            |      
| itemGroup.name.banner_pattern    |      
| itemGroup.name.bed               |      
| itemGroup.name.boat              |      
| itemGroup.name.boots             |      
| itemGroup.name.buttons           |      
| itemGroup.name.chalkboard        |      
| itemGroup.name.chest             |      
| itemGroup.name.chestplate        |      
| itemGroup.name.concrete          |      
| itemGroup.name.concretePowder    |      
| itemGroup.name.cookedFood        |      
| itemGroup.name.coral             |      
| itemGroup.name.coral_decorations |      
| itemGroup.name.crop              |     
| itemGroup.name.door              |      
| itemGroup.name.dye               |      
| itemGroup.name.enchantedBook     |      
| itemGroup.name.fence             |      
| itemGroup.name.fenceGate         |      
| itemGroup.name.firework          |      
| itemGroup.name.fireworkStars     |      
| itemGroup.name.flower            |      
| itemGroup.name.glass             |      
| itemGroup.name.glassPane         |      
| itemGroup.name.glazedTerracotta  |      
| itemGroup.name.grass             |      
| itemGroup.name.helmet            |      
| itemGroup.name.hoe               |      
| itemGroup.name.horseArmor        |      
| itemGroup.name.leaves            |      
| itemGroup.name.leggings          |      
| itemGroup.name.lingeringPotion   |      
| itemGroup.name.log               |      
| itemGroup.name.minecart          |      
| itemGroup.name.miscFood          |      
| itemGroup.name.mobEgg            |      
| itemGroup.name.monsterStoneEgg   |      
| itemGroup.name.mushroom          |      
| itemGroup.name.netherWartBlock   |      
| itemGroup.name.ore               |      
| itemGroup.name.permission        |      
| itemGroup.name.pickaxe           |      
| itemGroup.name.planks            |      
| itemGroup.name.potion            |      
| itemGroup.name.pressurePlate     |      
| itemGroup.name.rail              |      
| itemGroup.name.rawFood           |     
| itemGroup.name.record            |      
| itemGroup.name.sandstone         |      
| itemGroup.name.sapling           |      
| itemGroup.name.seed              |      
| itemGroup.name.shovel            |      
| itemGroup.name.shulkerBox        |      
| itemGroup.name.sign              |      
| itemGroup.name.skull             |     
| itemGroup.name.slab              |      
| itemGroup.name.splashPotion      |      
| itemGroup.name.stainedClay       |      
| itemGroup.name.stairs            |      
| itemGroup.name.stone             |      
| itemGroup.name.stoneBrick        |      
| itemGroup.name.sword             |      
| itemGroup.name.trapdoor          |      
| itemGroup.name.walls             |      
| itemGroup.name.wood              |      
| itemGroup.name.wool              |      
| itemGroup.name.woolCarpet        |      

