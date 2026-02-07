![[Lonely Sorrowsworn.webp]]
```statblock
name: Lonely Sorrowsworn
size: Medium
type: Monstrosity
alignment: Neutral Evil
ac: 16 (natural armor)
hp: 112
speed: 30 ft.
stats: [ 16, 12, 17, 6, 11, 6]
damage_resistances: bludgeoning, piercing, and slashing while in dim light or darkness
senses: Darkvision 60 ft., Passive Perception 10
languages: Common
cr: 9

traits:
  - name: Psychic Leech
    desc: At the start of each of the sorrowsworn's turns, each creature within 5 feet of it must succeed on a DC 15 Wisdom saving throw or take 10 (3d6) psychic damage.

  - name: Thrives on Company
    desc: The sorrowsworn has advantage on attack rolls while it is within 30 feet of at least two other creatures. It otherwise has disadvantage on attack rolls.

actions:
  - name: Multiattack
    desc: The sorrowsworn makes one Harpoon Arm attack, and it uses Sorrowful Embrace.
  - name: Harpoon Arm
    desc: _Melee Weapon Attack:_ +7 to hit, reach 60 ft., one target. _Hit:_ 21 (4d8 + 3) piercing damage, and the target is [grappled](https://5e.tools/conditionsdiseases.html#grappled_phb) (escape DC 15) if it is a Large or smaller creature. The sorrowsworn has two harpoon arms and can grapple up to two creatures at once.
  - name: Sorrowful Embrace
    desc: Each creature [grappled](https://5e.tools/conditionsdiseases.html#grappled_phb) by the sorrowsworn must make a DC 15 Wisdom saving throw, taking 18 (4d8) psychic damage on a failed save, or half as much damage on a successful one. In either case, the sorrowsworn pulls each of those creatures up to 30 feet straight toward it.
```