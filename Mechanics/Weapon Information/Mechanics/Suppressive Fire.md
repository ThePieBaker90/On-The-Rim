---
tags:
- tags_needed
---

## General Description
Suppressive fire is a special [fire mode](/Mechanics/Weapon%20Information/Mechanics/Fire%20Modes.md). Rather than aiming to damage opponents, it primarily serves to hinder the opponents' ability to fight back. Whereas ordinary fire modes represent a brief and controlled burst of fire, suppressive fire is sustained and continuous fire over the course of a combat round. 

## Mechanics

### Suppression
- Weapons capable of suppressive fire will have a suppressive fire zone specified, typically a cone for direct-fire weapons and an area for indirect-fire weapons.
  	- This zone lasts until the next turn of the creator.
- Any creature, character, etc. within the zone of fire and not in sufficiently hard cover makes a tiered dex save.
 	 - Before the roll, they may move to cover within half their movement speed. The dex roll is then made with disadvantage, but with the obscuration modifier from the cover.
  	- Targets with AV greater than the weapon's AP make the roll with advantage.
  	- Targets with AV greater than or equal to double the weapon's AP do not make this roll and are not affected by the zone of suppression.
  	- Targets inside vehicles do not make this roll and are not affected by the zone of suppression.
- The tiered dex save has the following result levels. The specific roll threshold for each level will be specified by the weapon.
	- On a critical failure (natural 1), the target is hit critically once and is suppressed.
 	- Below the lower threshold, the target is hit once and is suppressed.
      - If multiple types of ammunition are expended, select one at random in proportion to their portion of the total ammunition expended. How? That's on you to decide, you were the one to mix ammo types. 
  - Below the upper threshold, the target is suppressed.
  - Above or equal to the upper threshold, nothing happens.
- Additionally, any creature, character, etc that enters this zone or that decreases their obscuration modifier while in the zone rolls the tiered save.

### Belt-fed weapons
- On belt-fed weapons the amount of ammunition consumed by suppressive fire is a fixed amount.
  - If the weapon does not have that amount of ammunition remaining in its belt it cannot do suppressive fire.
- The thresholds for the tiered save are similarly fixed numbers, typically 12/18.
- Suppressive fire on a belt-fed weapon will typically affect [Barrel Heat](/Mechanics/Weapon%20Information/Mechanics/Barrel%20Heat.md)
### Magazine-fed weapons
- Magazine-fed weapons have a minimum ammunition requirement.
    - If the weapon does not have at least that amount of ammunition remaining in its magazine it cannot do suppressive fire, typically 10.
- All ammunition in the magazine will be expended during suppressive fire- for magazine-fed weapons, suppressive fire is a "mag dump".
- The mimimum ammunition expenditure will result in a minimum difficulty for the tiered save, typically 5/10.
    - For each certain amount of additional ammunition expended beyond the minimum, each threshold will increase in difficulty by one. The specific amount of additional ammunition expenditure required will be specified by the weapon, typically 2. Floor the result.
        - That is if the minimum ammunition requirement is 10 rounds and the user has 17 rounds in their magazine, all 17 rounds will be expended and the difficulty of all save thresholds will be increased by +3 (as 7/2 is floored to 3).

### The suppressed condition
- The Suppressed condition has the following effects:
    - All rolls are at disadvantage.
    - Movement speed is halved.
    - Concentration is impossible.
- The Suppressed condition can be removed by:
    - The creature, character, etc. no longer being within the zone of suppression, effective instantly
    - The creature, character, etc. may one time on their turn as a free action attempt a wisdom roll of equal difficulty as the high threshold of the tiered dex save.
        - On a failure, nothing happens.
        - On a success, the Suppressed condition is removed and the source of that condition will not retrigger suppression when e.g. leaving cover, for this creature, character, etc. this turn.
- Multiple sources may apply the Suppressed condition, for example, being inside multiple overlapping suppression zones and failing multiple of the associated saves.
    - The Suppressed condition and its effects do not stack with additional sources of the condition. One level of Suppressed has the same effect as 100.
    - However, to remove the Suppressed condition the target must be outside of *all* zones of suppression or must pass *all* wisdom rolls for active suppression sources from which they have the Suppressed condition.
        - In short, suppressive fire from multiple angles is not worse, but it is harder to evade or to willpower through.
