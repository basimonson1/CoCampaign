---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
aliases: ["Undead Spirit (Ghostly)"]
---
# [Undead Spirit (Ghostly)](z_Resources\CLI\bestiary\undead/undead-spirit-ghostly-xphb.md)
*Source: Player's Handbook (2024) p. 328*  

```statblock
"name": "Undead Spirit (Ghostly) (XPHB)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral"
"ac_class": "11 + the spell's level"
"stats":
- !!int "12"
- !!int "16"
- !!int "15"
- !!int "4"
- !!int "10"
- !!int "9"
"speed": "30 ft., fly 40 ft. (hover)"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[exhaustion](z_Resources/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](z_Resources/CLI/rules/conditions.md#Frightened), [paralyzed](z_Resources/CLI/rules/conditions.md#Paralyzed),\
  \ [poisoned](z_Resources/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "understands the languages you know"
"traits":
- "desc": "The spirit can move through other creatures and objects as if they were\
    \ Difficult Terrain. If it ends its turn inside an object, it is shunted to the\
    \ nearest unoccupied space and takes 1d10 Force damage for every 5 feet traveled."
  "name": "Incorporeal Passage"
"actions":
- "desc": "The spirit makes a number of attacks equal to half this spell's level (round\
    \ down)."
  "name": "Multiattack"
- "desc": "Melee Attack: YourSpellAttack Bonus equals your spell attack modifier,\
    \ reach 5 ft. Hit: 1d8 + 3 + the spell's level Necrotic damage, and the target\
    \ has the [Frightened](z_Resources/CLI/rules/conditions.md#Frightened) condition\
    \ until the end of its next turn."
  "name": "Deathly Touch"
"source":
- "XPHB"
```
^statblock