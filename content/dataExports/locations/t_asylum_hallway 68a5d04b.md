---
totemDataType: "location"
isInstance: false
---
# Hallway
Location ID: `000000000001bdc968a5d04b`
Group ID: `115da0827f29a3`
## Description
PLACEHOLDER
Is Spawn: false
Set Spawn on Enter: false
Set Spawn on Leave: false
Is Safe: false
Is PvP: true
Is Instanced: true
Danger Level: 3
## Connections
- [[t_asylum_cell_spawn 0d7c3fa9]] south
- [[t_asylum_courtyard d2f1c6c5]] north
## Entity Spawners
```js
{
  droptableId: 't_room_1_entities',
  spawnBehaviour: 'oneshot',
  spawnChance: 1,
  cooldown: -1,
  lastSpawnTime: 0,
  _id: new ObjectId('68b04b7d93a632cc1f401bdd')
}
```
- [[hollow_passive]] (2-2) ex: 2.00
## Loot Spawners
```js
{
  droptableId: 't_room_1_containers',
  spawnChance: 1,
  cooldown: -1,
  lastSpawnTime: 0,
  _id: new ObjectId('68b04b7d93a632cc1f401bde')
}
```
#### [[t_supplies_container_0]] (1-1) ex: 1.00
| Item | Min-Max | Expected |
|-|-|-|
| [[gw_[gs,ss0,ts,cs0,hammer]_[broken,common,old]_base_base]] | 1-1 | 1.00 |
| [[gw_[gs,halberd,hammer]_base_base_[]]] | 1-1 | 1.00 |
| [[ga_[vagabond,leather,hide]_[medarmour]_base_base]] | 1-1 | 1.00 |
| [[ga_[vagabond,leather,hide]_medgauntlets_base_base]] | 1-1 | 1.00 |
| [[ga_[vagabond,leather,hide]_leggings_base_base]] | 1-1 | 1.00 |
| [[potion_healing]] | 2-2 | 2.00 |
| [[bandage]] | 3-3 | 3.00 |
| [[gold_coin]] | 0-20 | 6.00 |
#### [[wooden_barrel]] (0-2) ex: 1.20
| Item | Min-Max | Expected |
|-|-|-|
| [[gold_coin]] | 0-25 | 7.50 |
| [[stick]] | 0-5 | 2.50 |
| [[red_berry]] | 0-5 | 3.75 |
| [[bandage]] | 0-1 | 0.20 |
| [[grease_fire]] | 0-6 | 0.59 |
| [[grease_lightning]] | 0-3 | 0.29 |
| [[grease_magic]] | 0-3 | 0.29 |
| [[grease_dark]] | 0-3 | 0.09 |
| [[grease_bleed]] | 0-3 | 0.05 |
| [[bug_pellet_magic]] | 0-5 | 0.25 |
| [[bug_pellet_fire]] | 0-5 | 0.25 |
| [[bug_pellet_lightning]] | 0-5 | 0.25 |
| [[bug_pellet_dark]] | 0-5 | 0.25 |
| [[gw_[]_[broken,old,common]_base_[base-100,bleed-5,burn-5,breakdefence-5,spinslash-10,openwound-10]]] | 0-1 | 0.02 |