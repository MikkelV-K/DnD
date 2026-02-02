![[Necromancer Wizard.webp]]
```statblock
name: Necromancer Wizard
size: Medium
type: humanoid
alignment: any evil
ac: 12 (15 with mage armor)
hp: 110
hit_dice: 13d8
speed: 30 ft.

stats:
  str: 9
  dex: 14
  con: 12
  int: 17
  wis: 12
  cha: 11

skillsaves:
  arcana: 7
  history: 7

senses: Passive Perception 11
languages: What is needed
cr: 9


actions:
  - name: Multiattack
    desc: The necromancer makes three Arcane Burst attacks.
  
  - name: Arcane Burst
    desc: _Melee or Ranged Spell Attack:_ +7 to hit, reach 5 ft. or range 120 ft., one target. _Hit:_ 25 (4d10 + 3) necrotic damage.

  - name: Spellcasting
    desc: >
      The necromancer casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 15):

       At will: [dancing lights](https://5e.tools/spells.html#dancing%20lights_phb), [mage hand](https://5e.tools/spells.html#mage%20hand_phb), [prestidigitation](https://5e.tools/spells.html#prestidigitation_phb)
    
       2/day each: [bestow curse](https://5e.tools/spells.html#bestow%20curse_phb), [dimension door](https://5e.tools/spells.html#dimension%20door_phb), [mage armor](https://5e.tools/spells.html#mage%20armor_phb), [web](https://5e.tools/spells.html#web_phb)
    
       1/day: [circle of death](https://5e.tools/spells.html#circle%20of%20death_phb)

bonus_actions:
  - name: Summon Undead (1/Day)
    desc: The necromancer magically summons five **skeletons** or **zombies**. The summoned creatures appear in unoccupied spaces within 60 feet of the necromancer, whom they obey. They take their turns immediately after the necromancer. Each lasts for 1 hour, until it or the necromancer dies, or until the necromancer dismisses it as a bonus action.
    
reactions:
  - name: Grim Harvest (1/Turn) 
    desc: When the necromancer kills a creature with necrotic damage, the necromancer regains 9 (2d8) hit points.
```
