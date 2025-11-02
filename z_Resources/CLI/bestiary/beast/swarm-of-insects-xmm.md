---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast
statblock: inline
aliases: ["Swarm of Insects"]
---
# [Swarm of Insects](z_Resources\CLI\bestiary\beast/swarm-of-insects-xmm.md)
*Source: Monster Manual (2024) p. 370*  

```statblock
"name": "Swarm of Insects (XMM)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "19"
"hit_dice": "3d8 + 6"
"stats":
- !!int "3"
- !!int "13"
- !!int "14"
- !!int "1"
- !!int "7"
- !!int "1"
"speed": "20 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](z_Resources/CLI/rules/conditions.md#Charmed), [frightened](z_Resources/CLI/rules/conditions.md#Frightened),\
  \ [grappled](z_Resources/CLI/rules/conditions.md#Grappled), [paralyzed](z_Resources/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](z_Resources/CLI/rules/conditions.md#Petrified), [prone](z_Resources/CLI/rules/conditions.md#Prone),\
  \ [restrained](z_Resources/CLI/rules/conditions.md#Restrained), [stunned](z_Resources/CLI/rules/conditions.md#Stunned)"
"senses": "blindsight 30 ft., passive Perception 8"
"languages": ""
"cr": "1/2"
"traits":
- "desc": "If the swarm has a [Climb Speed](z_Resources/CLI/rules/variant-rules/climb-speed-xphb.md),\
    \ the swarm can climb difficult surfaces, including along ceilings, without needing\
    \ to make an ability check."
  "name": "Spider Climb"
- "desc": "The swarm can occupy another creature's space and vice versa, and the swarm\
    \ can move through any opening large enough for a Tiny insect. The swarm can't\
    \ regain [Hit Points](z_Resources/CLI/rules/variant-rules/hit-points-xphb.md)\
    \ or gain [Temporary Hit Points](z_Resources/CLI/rules/variant-rules/temporary-hit-points-xphb.md)."
  "name": "Swarm"
"actions":
- "desc": "Melee Attack: +3, reach 5 ft. Hit: 6 (2d4 + 1) Poison damage, or\
    \ 3 (1d4 + 1) Poison damage if the swarm is [Bloodied](z_Resources/CLI/rules/variant-rules/bloodied-xphb.md)."
  "name": "Bites"
"source":
- "XMM"
```
^statblock

## Environment

desert, forest, grassland, hill, swamp, underdark, urban