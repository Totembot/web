---
totemDataType: "location"
isInstance: true
---
# Asylum Courtyard
Location ID: `68b04c6751b84433b0733299`
Group ID: `115da0827f29a3`
## Description
PLACEHOLDER
Is Spawn: false
Set Spawn on Enter: false
Set Spawn on Leave: true
Is Safe: false
Is PvP: true
Is Instanced: true
Danger Level: 4
## Connections
- [[t_asylum_hallway 68a5d04b]] south
- [[t_asylum_boss_room 38ab6926]] north
- [[t_asylum_east_wing 5b02c9a3]] east
## Entity Spawners
```js
{
  droptableId: 't_room_2_entities',
  spawnBehaviour: 'oneshot',
  spawnChance: 1,
  cooldown: -1,
  lastSpawnTime: 1756384360356,
  _id: new ObjectId('68b04b7d93a632cc1f401be8')
}
```
- [[hollow]] (1-1) ex: 1.00
## Loot Spawners
```js
{
  droptableId: 't_room_2_containers',
  spawnChance: 1,
  cooldown: -1,
  lastSpawnTime: 1756384360401,
  _id: new ObjectId('68b04b7d93a632cc1f401be9')
}
```
#### [[t_supplies_container_1]] (1-1) ex: 1.00
| Item | Min-Max | Expected |
|-|-|-|
| [[gold_coin]] | 0-30 | 9.00 |
| [[gw_[bow0,bow1]_[old,common,broken]_base_base]] | 1-1 | 1.00 |
| [[gw_arrow_base_base_base]] | 0-50 | 40.00 |
| [[gw_arrow_base_base_burn5]] | 0-20 | 16.00 |
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