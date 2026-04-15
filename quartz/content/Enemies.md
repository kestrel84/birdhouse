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
Summary:
- AC 17; HP 90; SPD 35
- Swipe: +6/2d6+5, +1 charge
- Charge: +2 charges
- Spin: 15ft radius, DEX 17/5d12, -3 charges

#### Grappler
- AC 15, HP 120; SPD 40
- Slam: +6/2d6+4
- Grapple: Athletics contest (+15). note: grappled creatures are moved with the grappler.
- Piledriver: +15/10d10, grappled creatures only
- Throw: Throws grappled creature 60ft away and deals 10d6 damage on impact. DEX 17/half damage and distance.

#### Caster
- AC 15; HP 70; SPD 25
- 4 crystals: pulsewave, fireball, lightning bolt, and hypnotic pattern
- Pulsewave: 30ft cone, 6d6+15ft away or towards caster. DEX 17/half damage and no distance.
- Fireball: 150ft range, 20ft sphere, DEX 17/8d6
- Lightning bolt: 100x5ft line, DEX 17/8d6
- Hypnotic pattern: 120ft range, 30ft cube, WIS 17/Charmed 1 min. Repeat at end of turn.
- Recharge: recharges all spent crystals
- Crystals can be targeted (AC 20); any damage permenantly destroys them

### Warper
- AC 17; HP 90; SPD 15
- Teleport: 100ft range, 1/every other turn, bonus action
- Plant bomb: plants a bomb on a player which detonates at the beginning of this enemy's next turn. Players can make a sleight of hand check to remove and throw the bomb, as an action.
- Bomb: 5ft radius, DEX 17/3d10

### Spiker
- AC 19; HP 70; SPD 30
- Spike Wall: chucks up a wall of thorns but spikier - 5ft long but as long and tall as I like. On appearance or ending turn in the wall: DEX 17/7d8. Moving through is double difficult terrain. 3/4 cover to entities on the other side.
- Ranged attack: ignores the wall, +6/2d6+5

### Flier
- AC 19; HP 110; SPD 40 (flying)
- Protect: attatches strings to three other enemies, buffing their AC by 5. Lasts until dispelled.
- Buff: gives an enemy advantage on their next attack.

### Polearm
- AC 17: HP 90; SPD 50
- Strike: +6/2d6+5, push 5ft. (can make two per turn)
- Impale: +3/5d6+10, target is grappled and restrained.
- Throw: Impaled creatures only. +3/5d6+10, target is thrown 30ft back.

### Artillerist
- AC 17; HP 70; SPD 30
- Bomb: Mortars a bomb over any obstacles if in free air, or LoS if not. Detonates at the beginning of their next turn - 15ft radius; DEX 17/5d10
- Firebomb: Mortars/shoots a bomb which detonates immediately, spreading fire in a 30ft radius. Creatures in the fire take 1d4 immediately, then if they start their turn in the fire, they take 1d6, then 1d8, etc, up to 1d20.

### Kraken
- AC 19; HP whatever; SPD 0
- 8 tentacles, each with 40 HP and 19 AC. All must be killed within one turn to kill the kraken.
- Each one has a gimmick:
  - One hits you (+7/3d10)
  - One grapples you (+10)
  - One shoots you (+7/3d10)
  - One stuns you (CON 17)
  - One poisons you (CON 17, 2d6/turn, save at end of turn)
  - One reduces AC and attack bonus (-5 AC, -5 attack)
  - One makes you vulnerable to damage (all damage)
  - One tries to hypnotic pattern you (WIS 19)
- Tentacles regrow with 10HP
