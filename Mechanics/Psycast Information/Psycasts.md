---
tags:
  - Info
aliases:
  - Psycast
---
## Psycast Overview
- Psycasts are the equivalent to spells and are how magic is done in this universe. Psycasts can only be used by creatures with a [[NOR-1 My First Psylink|Psylink]] (called psycasters or casters), be it installed, natural, or some other form. You must learn a psycast before you can use it.
## Psycast Phases
- The psycast has an order of phases that it goes through when used. 
- The order of phases is: Use -> Casting -> Cast -> Active -> End
	- Use (pay neural costs)
		- This is the phase the psycast starts out in when it is initially used. During this phase you pay the [[Neural Heat]] and [[Psyfocus]] costs of the psycast. This phase passes instantly to the casting phase if there are no interruptions.
	- Casting (pay component and casting time costs)
		- This phase lasts throughout the casting time of the psycast, during this time the psycast may be interrupted depending on the casting time (more details under [[#Casting Time]]). During this phase you satisfy the [[#Psycast Components|Psycast's Components]]. Once the casting time has elapsed, the psycast moves to the cast phase.
	- Cast (immediate effects)
		- This phase happens immediately after the casting phase has passed, during this phase the caster chooses targets, then, all immediate effects of the psycast occur (more details under [[#Psycast Effects]]) and you roll on the [[Exceeding the Neural Heat Limit|cast effect table]] if applicable. This phase passes to the active phase once all immediate effects are resolved. 
	- Active (recurring, passive, and delayed effects)
		- This phase happens after the cast phase, during this phase all recurring or passive effects from the psycast occur. Once the duration of the psycast passes, the phase passes to the end phase. 
	- End (effect end)
		- This phase happens after the active phase, during this phase all effects of the psycast end except effects that have their own duration. 
- If an effect forces a psycast into a phase, the phases before are skipped and their effects do not occur.
## Psycasting Modifier and Save DC
- There are two stats that may be referenced by psycasts, psycasting ability modifier and the psycast save DC.
	- A psycaster's psycasting ability modifier is determined by their class.
	- A psycaster's psycast save DC is 8 + their proficiency bonus + their psycasting ability modifier. 
		- All psycast saving throws without an explicit DC use the psycaster's psycast save DC as the save DC.
## Psycast Paths
- All psycasts belong to a path, the following is a comprehensive list of paths:
	- Damage Paths
		- [[Blazelord Psycasts|Blazelord]] - Fire Damage and Area Denial
		- [[Chemlord Psycasts|Chemlord]] - Corrosion Damage and Varied Chemicals
		- [[Frostlord Psycasts|Frostlord]] - Cold Damage and Freezing Anything
		- [[Mortilord Psycasts|Mortilord]] - Necrotic Damage and Negative Debuffs
		- [[Soundlord Psycasts|Soundlord]] - Sonic Damage and Music TODO
		- [[Staticlord Psycasts|Staticlord]] - Electrical Damage and Electronics TODO
		- [[Terralord Psycasts|Terralord]] - Bludgeoning Damage and Earth Shaping TODO
		- [[Toxilord Psycasts|Toxilord]] - Poison Damage and Stacking Damage Over Time
	- Creation Paths
		- [[Abominator Psycasts|Abominator]] - Summoning Abominations and Abomination Goo Manipulation
		- [[Aquator Psycasts|Aquator]] - Water Manipulation and Weather
		- [[Gravitor Psycasts|Gravitor]] - Force Creation and Energy Manipulation
		- [[Luzator Psycasts|Luzator]] - Light Creation and Information Revealing TODO
		- [[Technonator Psycasts|Technonator]] - Item Creation and Repairing TODO
		- [[Vegetator Psycasts|Vegetator]] - Plant Creation and Growth TODO
	- Utility Paths
		- [[Chronomancer Psycasts|Chronomancer]] - Time Manipulation and Prediction TODO
		- [[Harmomancer Psycasts|Harmomancer]] - Balance and Probability
		- [[Illusiomancer Psycasts|Illusiomancer]] - Illusion Creation and Sense Disabling TODO
		- [[Noctomancer Psycasts|Noctomancer]] - Darkness Manipulation and Stealth TODO
		- [[Puppetmancer Psycasts|Puppetmancer]] - Creature Commanding and Mind Meddling TODO
		- [[Skipmancer Psycasts|Skipmancer]] - Teleportation and Portals
		- [[Wildemancer Psycasts|Wildemancer]] - Animal Commands and Tracking TODO
	- Support Paths
		- [[Empath Psycasts|Empath]] - Emotions and Feelings
		- [[Hemopath Psycasts|Hemopath]] - Wound Manipulation and Bleeding TODO
		- [[Mendopath Psycasts|Mendopath]] - Healing and Stabilization
		- [[Neuropath Psycasts|Neuropath]] - Psycast and Neural Manipulation
		- [[Tegopath Psycasts|Tegopath]] - Damage Mitigation and Damage Debuffs TODO
		- [[Wagepath Psycasts|Wagepath]] - Damage Buffs and Accuracy Increases TODO
	- Each path contains 10 core psycasts of varying levels. To be able to learn a psycast from a path, you must know a psycast from the same path that is 1 level lower (for example, learning a level 3 psycast requires knowledge of a level 2 psycast). 
		- Level 1 is the lowest level for a psycast and has no prerequisites to learn. 
	- Some psycasts may be part of multiple paths, a prerequisite psycast from all paths must be known to learn these psycasts.
## Casting Time
- All psycasts have a casting time, there are two types of casting time; action based and time based. Each type of casting time details how the psycast is cast when used. 
	- Action based psycasts require the caster to expend the listed action type to cast the psycast (Action, Bonus Action, Reaction). The only way to interrupt these psycasts are with reactions.
	- Time based psycasts require the caster to be busy with the psycast for the casting time. When the specified time passes, the psycast casts. These psycasts can be interrupted with actions.
- If the caster is damaged during the casting time, they make a Wisdom saving throw. The DC is equal to 10 or half the damage received, whichever is higher. On a failure, the psycast is interrupted. On a success, nothing happens.
## Psycast Costs
- There are two resources that are concerned with casting psycasts, [[Neural Heat]] and [[Psyfocus]]. Both are detailed in-depth in their own documents. You pay these costs when you use the psycast but you do not roll on the [[Exceeding the Neural Heat Limit|cast effect table]] (if applicable) until you cast.
	- [[Neural Heat]] rapidly dissipates and limits how many psycasts you can cast in a short time.
	- [[Psyfocus]] is only regenerated on rest and limits how many psycasts you can cast before having to rest.
## Psycast Range
- All psycasts have a range, this is referred to by other properties such as targeting and has no inherent effects on the psycast.
	- "Self" means the psycast has no need for a range.
## Psycast Targeting
- All psycasts have a target, it determines what the caster can choose to be the target of the psycast. The target must be in the caster's line of sight unless otherwise stated and the target is determined when the psycast is cast.
	- "Self" refers to the caster.
	- "A creature" refers to a creature of the caster's choice.
	- "A point" refers to a point in space, this doesn't need to be grounded unless explicitly stated.
	- "Within range" means the target's distance to the caster must be under the psycast's range.
## Psycast Components
- All psycasts require components listed in that psycast's description, the components are as follows: Kinetic, Gesture, Verbal, Material, and Focus. The components must be satisfied during the [[#Casting Time]] of the psycast.
	- Kinetic components require the psycaster have one free hand.
		- Gesture components require the psycaster have two free hands. This component is incompatible with kinetic.
	- Verbal components require the psycaster to be able to speak.
	- Material components require that the psycaster has the listed items within their inventory, these items are not consumed unless explicitly stated.
	- Focus components require that the psycaster has the listed items equipped, these items are not consumed unless explicitly stated.
## Psycast Duration and Concentration
- All psycasts have a duration, the duration may be one of three types; Instant, $n$ turn, and time based. When the duration ends, the psycast moves into the end phase.
	- Instant psycasts have their effects occur immediately, they have no duration.
	- $n$ turn psycasts last until the end of the caster's $n$th turn from when the psycast was cast. The turn a psycast is cast is counted as the 1st turn.
	- time based psycasts last for the specified length of time from when the psycast was cast. If these are cast in combat, 6 seconds is equivalent to 1 turn.
	- Some psycasts may require concentration during the psycasts duration. Concentration may only be held on 1 psycast at a time. Concentration can be dispelled by the psycaster at anytime for free. 
		- While concentrating on some psycasts, your baseline [[Neural Heat]] may not drop below a specified amount. This amount is indicated in parenthesis next to the initial [[Neural Heat]] cost.
		- If you are hit while concentrating on a psycast you must make a Wisdom saving throw to continue concentrating. The DC is equal to 10 or half the damage of the attack, whichever is higher. On a failure, you lose concentration and the psycast moves to the end phase. On a success, nothing happens.
		- Some psycasts allow for concentrating on multiple instances of the psycast, each instance of this psycast being concentrated on adds to the baseline [[Neural Heat]] level by the specified amount.
## Psycast Effects
- There are four types of psycast effects; immediate, recurring, passive, and delayed. All effects will not occur if the psycast has ended 
	- Immediate effects occur only once, when the psycast enters the cast phase. 
		- For example, [[Cinder]] has only immediate effects.
	- Recurring effects are effects that may occur when a certain trigger condition is met, notably they may trigger multiple times. 
		- For example, [[Poison Cloud]] has a recurring effect for creatures starting their turn in the cloud, entering the cloud for the first time this turn, or ending their turn in the cloud.
	- Passive effects are always in effect while the psycast is active. 
		- For example, [[Levitation]] has only passive effects.
	- Delayed effects are effects that happen once after a certain trigger condition is met. They may not trigger if already triggered.
		- For example, [[Gravitic Flux|Gravitic Flux's]] slam is a delayed effect that uses the caster's next turn as its trigger condition.
## Upcasting
- Some psycasts may be upcast for an additional psyfocus cost specified in their description. The effects of upcasting are listed in each psycast's description.
	- Upcasting a psycast one time is called a first degree upcast, upcasting it two times is called a second degree upcast and so on.
## Interrupting
- Psycasts can be interrupted by many different effects. When a psycast is interrupted, the psycast immediately passes to the end phase. All costs already paid are not refunded.
## Psycasts and Stealth
- Psycasts may be used stealthily, the way a psycast is used in stealth depends on its components. When using a psycast from stealth, all other rules of stealth must be obeyed.
	- Psycasts containing a kinetic component require a dexterity (stealth) check against any relevant creature's [[Sight-Based Perception]]. 
		- Psycasts containing a gesture component require a dexterity (stealth) check at disadvantage against any relevant creature's [[Sight-Based Perception]]. 
	- Psycasts containing a verbal component require a charisma (stealth) check against any relevant creature's [[Sound-Based Perception]]. The psycasts range is halved when used in stealth.
	- Psycasts containing a material component require a dexterity (stealth) check against any relevant creature's [[Sight-Based Perception]]. 
	- Psycasts containing a focus component require a dexterity (stealth) check against any relevant creature's [[Sight-Based Perception]]. 
		- Psycasts that have a focus component which is an instrument have their range halved.