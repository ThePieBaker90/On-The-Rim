---
tags:
  - Info
---
## Stealth Overview
- Stealth and Hiding are the backbone for sneaking around unnoticed. All creatures can do any of the stealth actions (Hide, Sneak, Seek) for free as long as the conditions within the action are met.
## Hide Action
- You attempt to hide behind some [[#Obscuration]] within 5ft to avoid observation from enemies. This takes an action and you must make a Dexterity (stealth) check. The DC for this check is the [[#Obscuration]] base DC (Uses [[#Cover]], [[#Light]])
	- On a success, you become [[#Hidden]] by the [[#Obscuration]] by all creatures you are hiding from and you are no longer [[#Observed]] by those creatures. 
	- On a failure, TODO
## Sneak Action
- You attempt to sneak while [[#Hidden]], [[#Undetected]], or [[#Unnoticed]] to a second location. This takes 1 action to do. You then may move with each foot of movement costing 2ft of movement speed. Once you finish moving, you must make a Dexterity (stealth) check. The DC for this check is the [[#Obscuration]] base DC + the highest perception modifier among creatures that had line of sight to you during this action and that you are [[#Hidden]] from, [[#Undetected]] by, or [[#Unnoticed]] by. 
	- On a success, you become [[#Undetected]] if you were [[#Hidden]], otherwise you remain [[#Undetected]] or [[#Unnoticed]]. 
	- On a failure, you stay/become [[#Hidden]] or become [[#Observed]] if you failed critically.
## Seek Action
- You attempt to find an [[#Undetected]] creature. Choose either a 15ft sphere or a cone with a length of 30ft and a maximum width of 30ft. Then, make a Wisdom ([[Sight-Based Perception]], [[Scent-Based Perception]], or [[Sound-Based Perception]]) check. For every creature in the area, compare this result to the DC. The DC is the [[#Obscuration]] base DC + the stealth modifier of the creature. 
	- On success, you find the creature. They are [[#Observed]] by you if you can see them. Otherwise, they are [[#Hidden]] from you if you only know their location. 
	- On a failure, nothing happens.
## Obscuration
- Obscuration is how hard or easy your environment makes you to spot. 
- There are 5 types of obscurations; Cover, Light, Sound, Scent, and Effect obscurations.
- To find the obscuration base DC, simply add up the values of all relevant obscurations.
	- Relevant obscurations depend on the action and check that was made.
### Cover
- Cover is relevant for the [[#Hide Action]], the [[#Sneak Action]], and any [[Sight-Based Perception|Sight-Based]] [[#Seek Action|Seek Actions]].
- There are 5 types of cover; No cover, light cover, medium cover, heavy cover, and full cover.
#### No Cover
- A creature has no cover when they are less than 10% behind cover.
- This adds 10 to the obscuration base DC.
#### Light Cover
- A creature has light cover if they are less than 33% but more than or equal to 10% behind cover.
- This adds 6 to the obscuration base DC.
#### Medium Cover
- A creature has medium cover if they are less than 66% but more than or equal to 33% behind cover.
- This adds 3 to the obscuration base DC.
#### Heavy Cover
- A creature has heavy cover if they have less than 99% but more than or equal to 66% behind cover.
- This adds 0 to the obscuration base DC.
#### Full Cover
- A creature has full cover if they are more than 99% behind cover.
- .
### Light
- Light is relevant for the [[#Hide Action]], the [[#Sneak Action]], and any [[Sight-Based Perception|Sight-Based]] [[#Seek Action|Seek Actions]].
- There are 5 types of light; Bright light, dim light, darkness, and void darkness.
#### Bright Light
#### Dim Light
#### Darkness
#### Void Darkness
### Sound
- Sound is relevant for the [[#Sneak Action]], and any [[Sound-Based Perception|Sound-Based]] [[#Seek Action|Seek Actions]].
- There are 3 types of sound; Loud, Quiet, Ambient
### Scent
- Scent is relevant for any [[Scent-Based Perception|Scent-Based]] [[#Seek Action|Seek Actions]].
- There are 3 types of scent; Highly odorous, odorous, non-odorous.
### Effect
- Effect is any effects that may affect the obscuration base DC. The specifics of these effects are in each effect's description.
## Stealth States
- There are 4 states of stealth; observed, hidden, undetected, and unnoticed. These states determine what other creatures know about your whereabouts.
- Each state is in relevance to another creature. You may only be in one state at a time in relation to another creature, but may be in different states with different creatures.
	- For example, you can be hidden from one creature, observed by another, and undetected by a third. You cannot be hidden and undetected from the same creature.
### Observed
- A creature you are observed by knows exactly where you are. This has no effects.
### Hidden
- A creature you are hidden from knows the space you are in but cannot see you. Non-area of affect attacks on you by creatures you are hidden from have disadvantage to hit.
### Undetected
- A creature you are undetected by knows you are in the general vicinity but not you exact whereabouts. Non-area of affect attacks on you by creatures you are undetected by have disadvantage to hit. Attacks against creatures you are undetected by have advantage to hit.
### Unnoticed
- A creature you are unnoticed by is completely unaware of you. Creatures you are unnoticed by will not make attacks on you or seek you out. Attacks against creatures you are unnoticed by have advantage to hit.