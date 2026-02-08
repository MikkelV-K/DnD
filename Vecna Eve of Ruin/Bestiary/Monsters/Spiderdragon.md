![[Spiderdragon.avif]]
```statblock
name: Spiderdragon
size: Huge
type: Monstrosity
alignment: Chaotic Evil
ac: 17 (natural armor)
hp: 152
speed: 50 ft., Climn 60 ft.
stats: [ 21, 18, 16, 7, 14, 18]
skillsaves:
  - Intimidation: 8
  - Perception: 6  
damage_resistances: Poison, Psychic
senses: Darkvision 90 ft., Passive Perception 16
languages: Abyssal, Draconic, Undercommon
cr: 11

traits:
  - name: Magic Resistance
    desc: The spiderdragon has advantage on saving throws against spells and other magical effects.

  - name: Spider Climb
    desc: The spiderdragon can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.
    
  - name: Web Walker
    desc: The spiderdragon ignores movement restrictions caused by webbing.

actions:
  - name: Multiattack
    desc: The spiderdragon makes one Bite attack and two Claw attacks.
    
  - name: Bite
    desc: _Melee Weapon Attack:_ +9 to hit, reach 10 ft., one target. _Hit:_ 10 (1d10 + 5) piercing damage plus 13 (2d12) poison damage.
    
  - name: Claw
    desc: _Melee Weapon Attack:_ +9 to hit, reach 5 ft., one target. _Hit:_ 12 (2d6 + 5) slashing damage.
    
  - name: Spiderling Breath (Recharge 5–6)
    desc: The spiderdragon exhales venomous spiderlings in a 30-foot cone. Each creature in that area must make a DC 15 Dexterity saving throw, taking 33 (6d10) piercing damage and 33 (6d10) poison damage on a failed save or half as much damage on a successful one.
    
bonus_actions: 
  - name: Stifling Webs (Recharge 5-6)
    desc: >
      The spiderdragon spins a 30-foot cube of strong, sticky webbing in an area adjacent to itself. The webbing lasts for 1 minute, is difficult terrain, and lightly obscures its area. A creature that starts its turn in the webbing or enters the webbing for the first time on its turn must succeed on a DC 15 Dexterity saving throw or have the [restrained](https://5e.tools/conditionsdiseases.html#restrained_phb) condition while in the web. As an action, a creature can free itself or another creature from the web by succeeding on a DC 15 Strength check.

      A 5-foot cube of the web is destroyed if it takes at least 10 acid, fire, or slashing damage on a single turn.
```