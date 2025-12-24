---
tags:
  - Info
---
## Stealth Overview
- Stealth and Hiding are the backbone for sneaking around and doing things unnoticed. All creatures can do any of the stealth actions (Hide, Sneak, Seek) as long as the conditions within the action are met.
## Hide Action
- You attempt to hide behind some [[#Obscuration]] within 5ft to avoid observation from enemies. This takes an action and you must make a Dexterity (stealth) check. The DC for this check is the [[#Obscuration]] base DC.
	- On a success, you become [[#Hidden]] by the [[#Obscuration]] from all creatures you are hiding from and you are no longer [[#Observed]] by those creatures. 
	- On a failure, you fail to become [[#Hidden]] by the [[#Obscuration]]. You stay [[#Observed]]
## Sneak Action
- You attempt to sneak while [[#Hidden]], [[#Undetected]], or [[#Unnoticed]] to a second location. This takes 1 action to do. You then may move with each foot of movement costing 2ft of movement speed. Once you finish moving, you must make a Dexterity (stealth) check. The DC for this check is the [[#Obscuration]] base DC + the highest [[Sight-Based Perception]] modifier among creatures that had line of sight to you during this action and that you are [[#Hidden]] from, [[#Undetected]] by, or [[#Unnoticed]] by. 
	- On a success, you become [[#Undetected]] if you were [[#Hidden]], otherwise you remain [[#Undetected]] or [[#Unnoticed]]. 
	- On a failure, you stay/become [[#Hidden]] or become [[#Observed]] if you failed critically.
	- The relevant [[#Obscuration|Obscurations]] are the lighting, cover, and effects at your destination.
## Seek Action
- You attempt to find an [[#Undetected]] creature. Choose either a 15ft sphere or a cone with a length of 30ft and a maximum width of 30ft. Then, make a Wisdom ([[Sight-Based Perception]]) check. For every creature in the area, compare this result to the DC. The DC is a Dexterity (stealth) saving throw from the creature + the [[#Obscuration]] base DC of the [[#Undetected]] creature $*(-1)$
	- On success, you find the creature. They are [[#Observed]] by you if you can see them. Otherwise, they are [[#Hidden]] from you if you only know their location. 
	- On a failure, nothing happens.
## Obscuration
- Obscuration is how hard or easy your environment makes you to spot. 
- There are 5 types of obscurations; Cover, Light, and Effect obscurations.
- The obscuration base DC is used to represent how difficult it is to hide in an environment. To find the obscuration base DC, simply add up the obscuration modifiers of all relevant obscurations.

| Cover        | Obscuration Modifier | Light        | Obscuration Modifiers |
| ------------ | -------------------- | ------------ | --------------------- |
| No Cover     | 10                   | Bright Light | 10                    |
| Light Cover  | 8                    | Dim Light    | 4                     |
| Medium Cover | 3                    | Darkness     | 0                     |
| Heavy Cover  | 0                    | Void         | -20                   |
| Full Cover   | -3                   |              |                       |

### Cover
- Cover is relevant for the [[#Hide Action]], the [[#Sneak Action]], and any [[Sight-Based Perception|Sight-Based]] [[#Seek Action|Seek Actions]].
- There are 5 types of cover; No cover, light cover, medium cover, heavy cover, and full cover.
#### No Cover
- A creature has no cover when they are less than 10% behind cover.
- This has an obscuration modifier of 10.
#### Light Cover
- A creature has light cover if they are less than 33% but more than or equal to 10% behind cover.
- This has an obscuration modifier of 8.
#### Medium Cover
- A creature has medium cover if they are less than 66% but more than or equal to 33% behind cover.
- This has an obscuration modifier of 3.
#### Heavy Cover
- A creature has heavy cover if they have less than 99% but more than or equal to 66% behind cover.
- This has an obscuration modifier of 0.
#### Full Cover
- A creature has full cover if they are more than 99% behind cover.
- This has an obscuration modifier of -3.
### Light
- Light is relevant for the [[#Hide Action]], the [[#Sneak Action]], and any [[Sight-Based Perception|Sight-Based]] [[#Seek Action|Seek Actions]].
- There are 5 types of light; Bright light, dim light, darkness, and void.
#### Bright Light
- A creature is brightly lit while in [[Lighting#Bright Light|Bright Light]].
- This has an obscuration modifier of 10.
- See [[Lighting#Bright Light|Bright Light]]
#### Dim Light
- A creature is dimly lit while in [[Lighting#Dim Light|Dim Light]].
- This has an obscuration modifier of 4.
- See [[Lighting#Dim Light|Dim Light]]
#### Darkness
- A creature is in darkness while not in any light.
- This has an obscuration modifier of 0.
- See [[Lighting#Darkness|Darkness]]
#### Void 
- A creature is in void while in an effect that produces [[Lighting#Void|Void]].
- This has an obscuration modifier of -20.
- See [[Lighting#Void|Void]]
### Effect
- Effect is any effects that may affect the obscuration base DC. The specifics of these effects are in each effect's description.
## Stealth States
- There are 4 states of stealth; observed, hidden, undetected, and unnoticed. These states determine what other creatures know about your whereabouts.
- Each state is in relevance to another creature. You may only be in one state at a time in relation to another creature, but may be in different states with different creatures.
	- For example, you can be hidden from one creature, observed by another, and undetected by a third. You cannot be hidden and undetected from the same creature.
- You may rapidly swap stealth states with creatures in battle, an action does not need to specify you swap states for your to swap stealth states.
### Observed
- A creature you are observed by knows exactly where you are. This has no effects.
### Hidden
- A creature you are hidden from knows the space you are in but cannot see you. Non-area of affect attacks on you by creatures you are hidden from have disadvantage to hit.
### Undetected
- A creature you are undetected by knows you are in the general vicinity but not you exact whereabouts. Non-area of affect attacks on you by creatures you are undetected by have disadvantage to hit. Attacks against creatures you are undetected by have advantage to hit.
### Unnoticed
- A creature you are unnoticed by is completely unaware of you. Creatures you are unnoticed by will not make attacks on you or seek you out. Attacks against creatures you are unnoticed by have advantage to hit.