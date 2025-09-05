---
totemDataType: "location"
isInstance: false
---
# Wolfrun Graveyard
Location ID: `000000000000326d9710d0dc`
Group ID: `1df92645ba6ad5`
## Description
PLACEHOLDER
Is Spawn: false
Set Spawn on Enter: false
Set Spawn on Leave: false
Is Safe: false
Is PvP: false
Is Instanced: false
Danger Level: 6
## Connections
- [[asylum_grounds 8b841cd7]] north
- [[hub_church 47d655ff]] north
## Entity Spawners
```js
{
  droptableId: 'skeletons',
  spawnBehaviour: 'populate',
  spawnChance: 1,
  cooldown: 1200000,
  lastSpawnTime: 1756384531877,
  _id: new ObjectId('68b04b7e93a632cc1f401c09')
}
```
- [[skeleton]] (2-3) ex: 2.50
## Loot Spawners
```js
{
  droptableId: 'graves',
  spawnChance: 1,
  cooldown: 1200000,
  lastSpawnTime: 1756384531927,
  _id: new ObjectId('68b04b7e93a632cc1f401c0a')
}
```
#### [[grave]] (1-3) ex: 2.00
| Item | Min-Max | Expected |
|-|-|-|
| [[gold_coin]] | 0-1000 | 300.00 |
| [[human_bone]] | 0-5 | 2.50 |
| [[bone_ash]] | 0-5 | 2.50 |
| [[bandage]] | 0-1 | 0.20 |
| [[grease_bleed]] | 0-3 | 0.30 |
| [[gw_[]_[base,broken,old,common]_base_[base-100,bleed-5,burn-5,breakdefence-5,spinslash-10,openwound-10]]] | 0-2 | 0.04 |
| [[ga_[knight,chainmail,plate,light]_[helm,coif]_[base,ruined]_[base-15,strbuff,dexbuff,intbuff,faibuff,critbuff]]] | 0-1 | 0.02 |
| [[ga_[knight,chainmail,plate,light]_[armour,chestplate,Chestpiece,medarmour]_[base,ruined]_[base-15,strbuff,dexbuff,intbuff,faibuff,critbuff]]] | 0-1 | 0.02 |
| [[ga_[knight,chainmail,plate,light]_[medgauntlets,gauntlets]_[base,ruined]_[base-15,strbuff,dexbuff,intbuff,faibuff,critbuff]]] | 0-1 | 0.02 |
| [[ga_[knight,chainmail,plate,light]_[helm,coif]_[leggings,greaves]_[base-15,strbuff,dexbuff,intbuff,faibuff,critbuff]]] | 0-1 | 0.02 |