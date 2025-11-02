---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/plant
statblock: inline
aliases: ["Violet Fungus"]
---
# [Violet Fungus](z_Resources\CLI\bestiary\plant/violet-fungus-xmm.md)
*Source: Monster Manual (2024) p. 126*  

Slow but mobile, violet fungi rot any flesh they touch with their lashing tendrils.

## Fungi

*Deadly Spores and Predatory Polyps*

- **Habitat.** Underdark  
- **Treasure.** None  

The dank, sunless Underdark is a fertile breeding ground for weird and dangerous fungi.

```statblock
"name": "Violet Fungus (XMM)"
"size": "Medium"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "5"
"hp": !!int "18"
"hit_dice": "4d8"
"stats":
- !!int "3"
- !!int "1"
- !!int "10"
- !!int "1"
- !!int "3"
- !!int "1"
"speed": "5 ft."
"condition_immunities": "[blinded](z_Resources/CLI/rules/conditions.md#Blinded), [charmed](z_Resources/CLI/rules/conditions.md#Charmed),\
  \ [deafened](z_Resources/CLI/rules/conditions.md#Deafened), [frightened](z_Resources/CLI/rules/conditions.md#Frightened)"
"senses": "blindsight 30 ft., passive Perception 6"
"languages": ""
"cr": "1/4"
"actions":
- "desc": "The fungus makes two Rotting Touch attacks."
  "name": "Multiattack"
- "desc": "Melee Attack: +2, reach 10 ft. Hit: 4 (1d8) Necrotic damage."
  "name": "Rotting Touch"
"source":
- "XMM"
```
^statblock

## Environment

underdark