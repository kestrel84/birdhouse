## General
The play grid is upsised a 500x500ft grid, rather than a 5x5 one. The *Storm Chaser* (while only 60ish meters (~200ft) long) takes up a single space.

Damage is also upscaled and everything does *mega damage* - this is a gameplay distinction to account for the fact that your fireball or arrow is not going to do anything to a spelljammer hull, but a ballista is. The point is to keep damage numbers in reasonable ranges. For a rough idea, multiply mega damage by 100 to get regular damage, but this *isn't a gameplay feature and doesn't mean ballistae do 400 damage*. I get to decide when to use mega damage and when not to.
## Speed
Three types:
- **Tactical** - the only one available in combat. You move at 'reasonable' speeds and turn rates, per the ship's stat block; smaller ships are faster and more maneuverable than larger ships. Also the same speed you use when in close proximity to anything large.
- **Jammin** - the one you use to get between reasonably close planets and stations. Speed is exponential instead of linear, making it extremely hard to control precisely and functionally useless in combat.
- **Astral** - you are in a different dimension, which is much smaller than normal wildspace. Tactical speed works as normal, but jamming speed is hard to get up to if you're in a regular sea-sailing spelljammer and not usually necessary.

## Maneuverability
You can't move in any direction because, for instance, it takes more than six seconds to spin around a sixty-meter-long ship. Each ship has a value, called the **maneuverability**, which is an angle representing how quickly it can turn. This means that the direction your ship is facing is *important*. 

It works like this: every turn, you can move up to your movement to anywhere in a cone dictated by your maneuverability (see image below), and *then* rotate your ship by an amount of degrees equal to or less than your maneuverability.
![[ship combat movement cones.png]]
## Hull
Armour class works exactly the same as normal. Now ship HP isn't hit points, it's hull points, each of which is 100 regular hit points. One mega damage reduces hull points by one. Ships also have *bulwark points*, which are kind of like temporary hitpoints. They must be reduced to zero in order to start damaging hull points. A ship's bulwark points are replenished every turn as long as the ship has a boatswain (more on that [[#Classes|here]]).

Modules, weapons and other targetable parts like sails (where appropriate) each have ten hull points. Specific spelljammer class features can allow you to target the aforementioned. When disabled, a module/weapon/whatever must be restored to full HP in order be used again.

Hull points are hard to repair - every day, the boatswain can make a intelligence/(appropriate tools) check, DC 15. On success, repair HP equal to 10$\times$proficiency, on fail, repair half that. Can be used to repair the ship's main HP pool or to repair modules/weapons/whatever.

## Weapons
The fun part! Before we get started, remember that mega damage is its own thing, more or less separate from regular damage. 

Weapons are mounted on ship hardpoints. Each ship has a specific number of these, and they can be light, medium or heavy. Ship weapons are also light, medium and heavy, and can be mounted in any matching hardpoint or greater. So a cannonade (light) can be mounted on a light, medium or heavy hardpoint but a heavy dual ballista (heavy) can only be mounted on a heavy hardpoint.

Here's a summary of the weapons available:
![[ship weapons.png]]

Properties are as follows:
- **Automatic**: For each normal attack you make with this weapon inside its normal range, you can instead choose to make two attacks at disadvantage. These attacks always have disadvantage, regardless of circumstance.
- **Ammo**: You need ammo and consume one each time you attack with this weapon.
- **Deployable**: These weapons release something onto the battlefield, for instance mines. When you attack with these, you release whatever's deployed within 500ft of your vessel (so, in an adjacent square). When an enemy contacts the deployable, make a ship weapon attack against it; the deployable is destroyed.
- **Loading**: Same as normal; you can only fire this once per action or bonus action. 
- **Overheat**: Once you make an attack with this weapon, it can't be used again until your next turn.
- **Backfire**: If the unmodified dice roll for an attack is equal to or lower than the backfire value, the weapon blows up. You are not harmed.
- **Crew**: Ignore this one

## Modules
These are cool. Each module takes up an amount of cargo capacity but other than that they do whatever they say they do. See the wildjammer book for all of them; highlights include a magic amplifier which lets you cast *mega fireball*.

## Upgrades
Upgrades to existing weaponry, hull, engines, whatever. Basically do what they say they do, see the wildjammer book for a full list.

## Fore mantle
The place you put a figurehead. Can also be used for mounting things like rams and grappling arms. The *Storm Chaser* comes with a sickle-shaped front which works like a Ram.

## Bridge Crew Roles
First, a note: anything referencing a *Ship Weapon Attack* works like this:
- Roll attack and add str or dex (your choice) plus proficiency.
- Roll damage according to the weapon but *don't add a modifier*.
- You may use class features like divine smite, reckless attack and extra attack while making ship weapon attacks.

You start with 4 points to put into these roles, and you gain 2 more at levels 5, 9, 13 and 17. Your role determines what actions you can do on your turn; in a given combat you can only play one role. Everyone starts at rank 0 (which does still confer some features). There are five classes:
- The Boatswain - aka (in my opinion) the engineer. Responsible for repairs and the proper operation of the propulsion and maneuvering systems.
- The Captain - coordinates the crew and boosts their abilities.
- The Fighter Helmsman - deploys and flies small fighters to harass enemy ships.
- The Gunner - have command of the ship weapons
- The Helmsman - flies the damn ship
See the wildjammer book for details on each role's abilities.