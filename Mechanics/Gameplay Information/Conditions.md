---
tags:
  - Info
aliases:
  - Condition
---
## Condition Overview
- Conditions are effects that affect a creature. A creature may have an unlimited amount of conditions affecting them, although all non-[[#Stacking Conditions]] cannot have multiple instances on that creature. 
- All (non-status) conditions are either positive, negative, or mixed. This determines what effects interact with the condition.
## Duration
- All conditions have a duration which may be measured in turns or may be indefinite.
- When a creature ends its turn, the duration of all conditions on the creature decrease by 1 turn. Any conditions that have a duration of 0 turns are removed.
	- Conditions with indefinite duration do not decrease their duration, they may only be removed by effects.
## Statuses
- Statuses are a form of conditions that cannot be removed by most condition removing effects. They can only be removed in the following ways:
	- Effects that explicitly affect statuses.
	- Effects that name the specific status.
	- Effects within the status itself.
	- Effects from a condition granting the status.
- Statuses are neither positive, negative or mixed.
## Stacking Conditions
- Some conditions may stack, this means that the condition has an associated level, this level can be increased or decreased as specified in any relevant effect's description. 
	- This level may be capped or uncapped for certain conditions.
	- For example, [[Radiation Buildup]] is a stacking condition.
## Condition Effects
- Condition effects can be sorted into 6 different types: [[#Passive Effects]], [[#Ability Effects]], [[#Condition Granting Effects]], [[#Start of Turn Effects]], [[#End of Turn Effects]], and [[#Triggered Effects]].
- These effect descriptions also apply to [[#Statuses]].
### Passive Effects
- Passive effects are always in effect while a creature has the condition.
	- For example, [[Blinded]] has only passive effects.
### Ability Effects
- Ability effects grant the creature with the condition an ability of some kind.
	- For example, [[Skipping]] has only an ability effect.
### Condition Granting Effects
- Condition granting effects give the creature who has the condition additional conditions or statuses. These conditions and statuses remove themselves when the condition they came from is removed (unless another effect gave the creature that condition or status).
	- For example, [[Flashed]] has only condition granting effects.
### Start of Turn Effects
- Start of turn effects are effects that specify "at the start of their turn," specifically the effect happens when the affected creature begins their turn.
	- For example, [[On Fire!|On Fire!'s]] damage is a start of turn effect.
### End of Turn Effects
- End of turn effects are effects that specify "per turn," specifically the effect happens when the affected creature ends their turn.
	- For example, [[Poison Buildup|Poison Buildup's]] damage is an end of turn effect.
### Triggered Effects
- Triggered effects occur when a condition or event specified by the effect occurs.
	- For example, [[Burned]] has a triggered effect for dousing the affected creature in water.
## Condition Immunities
- Some conditions may state that a creature who fulfills a specified criteria is immune to the condition. A creature who is immune to the condition cannot have that condition. If the condition is granted to them, no effects occur and any effects that trigger when a condition is granted do not trigger.
- Some conditions grant creatures immunity to other conditions.
	- If a creature would be granted a condition, condition A, granting them immunity to another condition, condition B, which they already have, that immunity is enforced and condition B is lost.
		- For example, if a creature has [[Inspiration]] and is granted [[Panic]], they lose [[Inspiration]] due to the immunity granted by [[Panic]].
		- However if condition B also has an immunity to condition A, the condition that has been affecting the creature the longest stays, therefore now condition B stays and condition A is blocked from being granted.
			- For example, if a creature has [[Energized]] and is granted [[Lethargic]], [[Lethargic]] is blocked from being granted due to the immunity from [[Energized]].