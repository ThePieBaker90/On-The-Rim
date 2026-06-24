---
tags:
- tags_needed
---
## General Description
Certain weapons, primarily belt-fed ones with a high rate of fire, generate heat during operation. This heat has detrimental effects on the accuracy and reliability of the weapon. This heat may dissapate passively or require active cooling.

## Mechanics

- Heat generation
	- Each fire mode of the weapon will have some heat generation specified by the weapon.
 		- Typically, 2 for suppressive fire, 0 for automatic fire, -1 for burst fire.
 	- When that fire mode is used the weapon's heat will increase by that number.
  	- A fire mode may have a negative heat generation; in that case, the heat "generation" is negative and therefore a decrease.
  - Heat dissipation
  	- The weapon will have typically have a passive heat dissapation, where the heat decreases if the barrel is not used for a combat round.
   		- This is typically a flat number but may be a fraction in which case the amount of heat dissapated is rounded upwards.
     		- Typically 3 or half 
     - Additionally there may be actions that can be taken to actively reduce the heat on the weapon.
  - Heat capacity
  	- The weapon will have a speicified heat capacity as some die or dice.
   		- Typically 1D6
     - After using suppressive fire, roll the heat capacity dice. If the roll is less than the current heat, the weapon is [Jammed](/Conditions/Non-Creature%20Conditions/Weapon/Jammed.md). This jam does not interfere with the suppressive fire that caused it but occurs afterwards.
  - Other effects of heat
     - Accuracy of the weapon is decreased with a -1 to hit per unit heat on the weapon.
     - On a failed unjamming check the user takes thermal damage equal to the weapon's heat.
