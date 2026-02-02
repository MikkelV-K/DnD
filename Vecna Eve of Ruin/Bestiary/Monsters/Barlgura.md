![[Barlgura.webp]]

```statblock
name: Barlgura
size: Large
type: fiend(Demon)
alignment: chaotic evil
ac: 15 (natural armor)
hp: 68
hit_dice: 8d10 + 24
speed: 40 ft., climb 40 ft.

stats:
  str: 18
  dex: 15
  con: 16
  int: 7
  wis: 14
  cha: 9

saves:
  dex: 5
  con: 6

skillsaves: 
  Perception: 5
  Stealth: 5

damage_resistances: cold,fire, lightning
damage_immuities: poison
condition_immunities: poisoned

senses: blindsight 30 ft., darkvision 120 ft.
languages: Abyssal
cr: 5

traits:
  - name: Innate Spellcasting
    desc: >
      The barlgura's spellcasting ability is Wisdom (spell save DC 13). The barlgura can innately cast the following spells, requiring no material components:
      
      1/day each: _[entangle](https://www.aidedd.org/dnd/sorts.php?vo=entangle), [phantasmal force](https://www.aidedd.org/dnd/sorts.php?vo=phantasmal-force)_
      
      2/day each: _[disguise self](https://www.aidedd.org/dnd/sorts.php?vo=disguise-self), [invisibility](https://www.aidedd.org/dnd/sorts.php?vo=invisibility)_ (self only)
  - name: Reckless
    desc: >
      At the start of its turn, the barlgura can gain advantage
      on all melee weapon attack rolls during that turn, but
      attack rolls against it have advantage until the start
      of its next turn.
  - name: Running Leap
    desc: "The barlgura's long jump is up to 40 feet and its high jump is up to 20 feet when it has a running start."

actions:
  - name: Multiattack
    desc: >
      The barlgura makes three attacks: one with its bite and
      two with its fists.
  - name: Bite
    desc: "_Melee Weapon Attack_: +7 to hit, reach 5 ft., one target. _Hit_: 11 (2d6 + 4) piercing damage."
  - name: Fist
    desc: "_Melee Weapon Attack_: +7 to hit, reach 5 ft., one target. _Hit_: 9 (1d10 + 4) bludgeoning damage."

```