---
tags:
  - Info
  - Drug
aliases:
  - Drug
---
## Drug Overview
- Drugs are substances which creatures can consume in various forms to gain temporary effects at the risk of addiction.
- There are three categories a drug may fall in to: social drugs, medical drugs, and hard drugs.
	- Social drugs only start a [[#Drug Addiction]] on seasoned users and [[#Overdosing]] is a rarity.
	- Medical drugs can never start a [[#Drug Addiction]] on a first use, although [[#Overdosing]] and [[#Drug Addiction]] is much more of a concern on continued use.
	- Hard drugs can cause an [[#Overdosing|Overdose]] or [[#Drug Addiction]] at any time and are considered socially taboo.
- Drugs take two forms; consumables and substances. 
	- Consumables are items that contain an associated substance and other stats. They are items that can be found and bought. When used, they inflict the user with the substance's usage effects. 
	- Substances are the generic form of the drug and hold its usage effects, addiction effects, tolerance effects and other related information. Substances are not items and cannot be found or used like a consumable.
## Drug Usage
- When a drug is used, several effects occur to the user immediately. The effects in order:
	- The [[#Drug Effects]] begin on the user. The effects last for the [[#High Duration]], adjusted by the user's [[#Drug Tolerance]].
	- The user's [[#Drug Tolerance]] is adjusted (if applicable).
	- The user's [[#Withdrawal]] is adjusted (if applicable).
	- The user makes an [[#Addiction Roll]]. (if applicable.)
	- The user makes an [[#Overdose Roll]] (if applicable).
### Drug Effects
- .
### High Duration
- .
## Drug Tolerance
- Using certain drugs causes the user to build up a tolerance to the drug. Tolerance affects the length of the [[#High Duration]] from using a drug, tolerance increases when the drug is used and decreases when the user rests. 
- The tracked tolerance number for each drug is measured as a percent from 0% to 75% with up to one decimal place. 
- When a user uses a drug they do not have a tolerance for, they begin tracking a tolerance number corresponding to the drug. This number starts at 0 and is not adjusted on a first use by using the drug.
- When the user uses a drug they have a tolerance for, the [[#High Duration]] is reduced by their drug tolerance for the drug.
- Additional effects may occur in certain ranges of drug tolerance as listed in the substance's drug tolerance field.
- When the user's drug tolerance is adjusted, the following occurs on their tracked tolerance.
	- If it was due to their use of a drug, their tracked tolerance number for the corresponding drug is adjusted by the "on use." value indicated in the substance's drug tolerance field. 
	- If it was due to them resting, the tracked tolerance numbers for all drugs decrease by 2.5%.
## Drug Addiction
- Using certain drugs can create a drug addiction, causing the user to have a need for the substance or go through the nasty process of [[#Withdrawal]]. 
- When a user uses a drug they do not have a drug addiction to, they make an [[#Addiction Roll]] to see if they create a drug addiction.
- When a user has a drug addiction, they suffer the effects listed in the substances addiction effects field.
### Addiction Roll
- Some effects may make a user make an addiction roll. Addiction rolls are to see if the user gets addicted to the drug on this use.
- When a user makes an addiction roll, the following happens in order:
	- They roll 1d100.
	- All relevant effects are applied to the result.
	- The result is compared to the [[#Addiction Threshold]] of the drug.
		- If it is less than or equal to the threshold, they create a [[#Drug Addiction]] to the used drug.
		- If it is greater than the threshold, nothing happens.
### Addiction Threshold
- The addiction threshold of a drug is the highest result that can come from an [[#Addiction Roll]] which will cause the user to create a [[#Drug Addiction]].
- This value can be modified by various effects.
- An addiction threshold of 0 means the drug is non-addictive and cannot cause its user to create a [[#Drug Addiction]].
### Withdrawal
- .
## Overdose
- .
### Overdose Roll
- Some effects may make a user make an overdose roll. Addiction rolls are to see if the user overdoses on the drug on this use.
- When a user makes an overdose roll, the following happens in order:
	- They roll 1d100.
	- All relevant effects are applied to the result.
	- The result is compared to the [[#Overdose Threshold]] of the drug.
		- If it is less than or equal to the threshold, ...
		- If it is greater than the threshold, nothing happens.
### Overdose Threshold
- .
