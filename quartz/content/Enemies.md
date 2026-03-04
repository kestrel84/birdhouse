### General Features
All remnants can be controlled by a person of sufficient power using a specialised spell (details coming soon.)


### Low tier
- Melee (Remnant)
	- Think goblin or bandit
- Ranged (Remnant)
	- Think goblin or bandit but with a bow
- Mortar
	- Shoots every other turn but deals aoe damage bypassing cover
- AoE mage
	- For low levels, acid splash and shatter should suffice
- Potion-thrower (Area denial)
	- Throws down acid and fire potions which reduce ac and deal damage respectively
- Control mage (?)
	- Casts annoying shit like sleep

#### Remnant
```statblock
name: Remnant
source: me
size: Medium
type: humanoid
//subtype: any race
alignment: chaotic evil
ac: 12
hp: 11
speed: 30 ft.
stats:
  - 11
  - 12
  - 12
  - 10
  - 10
  - 10
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: Passive Perception 10
languages: none
cr: 1/8
bestiary: true
actions:
  - name: Blade Arm
    desc: "Melee Weapon Attack: +3 to hit, reach 5, one target, 1d6 + 1 slashing"
    attack_bonus: 3
    damage_dice: 1d6
    damage_bonus: 1
```

#### Remnant Gunner
```statblock
name: Remnant Gunner
source: me
size: Medium
type: humanoid
//subtype: any race
alignment: chaotic evil
ac: 13
hp: 10
speed: 30 ft.
stats:
  - 11
  - 12
  - 12
  - 10
  - 10
  - 10
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: Passive Perception 10
languages: none
cr: 1/8
bestiary: true
actions:
  - name: Crystal Shot
    desc: "Ranged Attack: +3 to hit, range 80/320, one target, 1d8 + 1 piercing"
    attack_bonus: 3
    damage_dice: 1d8
    damage_bonus: 1

```
#### Remnant Bomber
```statblock
name: Remnant Bomber
source: me
size: Medium
type: humanoid
//subtype: any race
alignment: chaotic evil
ac: 14
hp: 15
speed: 30 ft.
stats:
  - 11
  - 12
  - 12
  - 10
  - 10
  - 10
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: Passive Perception 10
languages: none
cr: 1/4
bestiary: true
actions:
  - name: Phase Strike
    desc: "Ranged Attack: +3 to hit, range 40/160 (goes through cover and walls), one target, 1d8 + 1 force"
    attack_bonus: 3
    damage_dice: 1d8
    damage_bonus: 1
  - name: Phase Bomb
    desc: "cast range 30 (goes through cover and walls), explosion range 10. DC 12 DEX, 2d6 force, half on save. 4/Combat"
    attack_bonus: 0
    damage_dice: 1d8
```


**ELITES**
#### Remnant Alpha
```statblock
name: Remnant Alpha
source: me
size: Medium
type: humanoid
//subtype: any race
alignment: chaotic evil
ac: 15
hp: 65
hit_dice: 10d8 + 20
speed: 30 ft.
stats:
  - 15
  - 16
  - 14
  - 14
  - 11
  - 14
saves:
  - strength: 4
  - dexterity: 5
  - wisdom: 2
skillsaves:
  - athletics: 4
  - deception: 4
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: Passive Perception 10
languages: none
cr: "2"
bestiary: true
actions:
  - name: Multiattack
    desc: "Two blade arm attacks and one knee attack"
    attack_bonus: 0
  - name: Blade Arm
    desc: "Melee Weapon Attack: +5 to hit, reach 5, one target, 1d6 + 3 slashing"
    attack_bonus: 5
    damage_dice: 1d6
    damage_bonus: 3
  - name: Knee
    desc: "Melee Weapon Attack: +5 to hit, reach 5, one target, 1d4 + 3 bludgeoning"
    attack_bonus: 5
    damage_dice: 1d4
    damage_bonus: 3
  - name: Shard Throw
    desc: "The alpha throws an explosive crystal shard. throw range 60, explosion 10. DC 12 DEX save, 3d4 piercing damage, half on success."
    attack_bonus: 0
    damage_dice: 3d4
reactions:
  - name: Parry
    desc: +2 AC vs one melee attack that would hit.
    attack_bonus: 0
```

#### Remnant Shapechanger
```statblock
name: Remnant Shapechanger
source: me
size: Medium
type: monstrosity
subtype: shapechanger
alignment: unaligned
ac: 14
hp: 52
hit_dice: 8d8 + 16
speed: 30 ft.
stats:
  - 11
  - 18
  - 14
  - 11
  - 12
  - 14
skillsaves:
  - deception: 6
  - insight: 3
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: charmed
condition_immunities: ""
senses: darkvision 60 ft., passive Perception 11
languages: Common
cr: "3"
bestiary: true
traits:
  - name: Shapechanger
    desc: The remnant can use its action to polymorph into a Small or Medium humanoid it has seen, or back into its true form. Its statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.
    attack_bonus: 0
  - name: Ambusher
    desc: Advantage on attack rolls against any creature it has surprised.
    attack_bonus: 0
  - name: Surprise Attack
    desc: If the doppelganger surprises a creature and hits it with an attack during the first round of combat, the target takes 3d6 extra damage
    attack_bonus: 0
    damage_dice: 3d6
actions:
  - name: Multiattack
    desc: The doppelganger makes two melee attacks.
    attack_bonus: 0
  - name: Slam
    desc: "Melee Weapon Attack: +6 to hit, reach 5, one target, 1d6 + 4 bludgeoning"
    attack_bonus: 6
    damage_dice: 1d6
    damage_bonus: 4
  - name: Read Thoughts
    desc: The doppelganger magically reads the surface thoughts of one creature within 60 ft. of it. The effect can penetrate barriers, but 3 ft. of wood or dirt, 2 ft. of stone, 2 inches of metal, or a thin sheet of lead blocks it. While the target is in range, the doppelganger can continue reading its thoughts, as long as the doppelganger's concentration isn't broken (as if concentrating on a spell). While reading the target's mind, the doppelganger has advantage on Wisdom (Insight) and Charisma (Deception, Intimidation, and Persuasion) checks against the target.
    attack_bonus: 0

```

- Melee
	- Bandit captain
- Gimmick
	- Shapechanger


### Mid tier
These should be able to give a level five party a run for their money. Also, more gimmicky enemies, the bomber got really good feedback. More like that.

Plus, don't be afraid to have obvious gimmicks and different-looking enemies; it helps a lot with differentiation.

Concepts:
- **Charger** - charges up to a big super duper attack. It has three palm-sized glowing crystals  on both its front and back, which start glowing to indicate charge level. three moves:
	- whack, possibly also ranged whack of some kind (gain one charge)
	- charge (gain two charges)
	- super hit (costs three charges)
- **Grappler** - always attempts to grapple a player and then deal massive damage (piledriver ass attack). Has four arms.
- **Warper** - plants bombs on the players, which they have to unstick. Has a teleport move, invis (?) and a weak melee attack. very rougeish, has a cape of mist.
- **Spiker** - uses wall of thorns, flavoured and balanced appropriately (crystal spikes?). Attempts to wall off the players and then throw spikes at them from behind it. Spiky boi in general, damages you on it. 
- **Flier** - buffs the others and flies around like a bastard (but no healing). undecided between ATK/DMG straight +number or a buff to the number of dice rolled. Has long strings of crystals, which wave round as it flies, and attatch to whichever unit it buffs. 
- **Artillerist** - has a bigger version (three square radius at least) of the delayed blast bombs, as well as instant fiery bombs.
- **Caster** - has four crystals floating in an arc above its head (?). One is blue lightning (lightning bolt), one is orange fire (fireball), one is swirling air ([pulse wave](https://dnd5e.wikidot.com/spell:pulse-wave)), and one is pink swirls (hypnotic pattern). It can cast any of the spells in its crystals once, causing the crystal to go out, and it can spend an action recharging any spent crystal.
- **Summoner** - summons a golem with a pike (so 10ft opportunity attack range lmaoo) and a large HP pool, but not much damage. Kill the summoner to kill the golem. The summoner's a short ass mfer with a flag and can also buff the summon after summoning it.
- **Illusionist** - summons four additional copies of itself (all of which have real attacks). The real one is signified by a correct wisdom check, the DC of which goes down as the players repeat it. 
- **Debilitator** - a debuffer of some kind who inflicts various debuffs on the party. Be careful with this one, could get extremely frustrating. Can inflict poison, stun, and frightened at least, plus some other less annoying ones. Chucks tiny crystals which can be removed by yourself (if the condition allows it) and by other players for an action, removing the debuff. 

Stats subject to change lmao

#### Charger
```statblock
name: Remnant Charger
source: me
size: Medium
type: monstrosity
alignment: unaligned
ac: 17
hp: 90
speed: 35 ft.
stats:
  - 18
  - 12
  - 16
  - 11
  - 12
  - 11
saves:
  - strength: 8
  - constitution: 6
skillsaves:
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
senses: darkvision 60 ft., passive Perception 11
languages: None
cr: 5
bestiary: true
traits:
  - name: Charging
    desc: The Charger has three crystals, which can light up. It lights up one on a melee attack and two when it spends its turn charging. With three charges, it can enlarge its greatsword and spin around, attacking a large area.
actions:
  - name: Swipe
    desc: "Melee Weapon Attack: +6 to hit, reach 5, one target, 2d6 + 4 slashing"
    attack_bonus: 6
    damage_dice: 2d6
    damage_bonus: 4
  - name: Charge
    desc: "The Charger focuses, gaining two charges."
  - name: "Charged Spin"
    desc: "Requires three charges. The Charger channels the energy stored in its crystals into its greatsword, enlarging it. It then spins around in a massive attack. Everyone within fifteen feet of the Charger makes a DC 17 DEX save and takes 5d12 slashing damage on a failed save, half as much on a success."
    attack_bonus: 0
    damage_dice: 5d12
```


#### Grappler
```statblock
name: Remnant Grappler
source: me
size: Large
type: monstrosity
alignment: unaligned
ac: 15
hp: 120
speed: 40 ft.
stats:
  - 22
  - 12
  - 13
  - 11
  - 12
  - 11
saves:
  - strength: 8
  - constitution: 6
skillsaves:
  - athletics: 10
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
senses: darkvision 60 ft., passive Perception 11
languages: None
cr: 5
bestiary: true
actions:
  - name: Slam
    desc: "Melee Weapon Attack: +6 to hit, reach 5, one target, 2d6 + 4 bludgeoning"
    attack_bonus: 6
    damage_dice: 2d6
    damage_bonus: 4
  - name: "Grapple"
    desc: "The Grappler attempts to grapple a humanoid. It makes a contested strength (Athletics) check on a creature of large or smaller. If it succeeds, the creature is grappled."
    attack_bonus: 0
  - name: "Piledriver"
    desc: "The grappler takes a creature it has grappled, then leaps up and slams it into the ground. Makes a melee weapon attack: +15 to hit, grappled target, 10d10 blugeoning damage"
    damaage_dice: 10d10
```


#### Caster
```statblock
name: Remnant Caster
source: me
size: Medium
type: monstrosity
alignment: unaligned
ac: 15
hp: 70
speed: 25 ft.
stats:
  - 10
  - 14
  - 13
  - 20
  - 18
  - 11
saves:
  - constitution: 6
  - wisdom: 8
  - intelligence: 10
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
senses: darkvision 60 ft., passive Perception 11
languages: None
cr: 5
bestiary: true
traits:
  - name: Power Crystals
    desc: The Caster has four crystals floating in an arc above its head. Each one is a different color - blue lightning, orange fire, pink swirls, and white air. When it casts the spell for that crystal (lightning bolt, fireball, hypnotic pattern, and pulse wave respectively) then the crystal goes dark.
actions:
  - name: Cast
    desc: "Casts the spell from a lit-up crystal. Reference: LB: self, 100x5 line, DC17 DEX, 8d6 lightning. FB: 150 range, 20 radius, DC17 DEX, 8d6 fire. HP: 120 range, 30 cube, DC17 WIS, charmed for 1 min. end on damage or help actionPW: self, 30 cone, DC 17, 6d6 force + pull/push 15ft"   
    attack_bonus: 0
  - name: "Recharge"
    desc: "The caster spends its turn recharging a spent crystal."
    attack_bonus: 0
  - name: "Piledriver"
    desc: "The grappler takes a creature it has grappled, then leaps up and slams it into the ground. Makes a melee weapon attack: +15 to hit, grappled target, 10d10 blugeoning damage"
    damage_dice: 10d10
```
