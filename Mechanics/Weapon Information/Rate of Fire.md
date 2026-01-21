---
tags:
  - Info
aliases:
  - ROF
---
## Rate of Fire Overview
- Rate of fire is a stat that all weapons have that represents how many times a weapon attacks when used.
- Rate of fire (frequently abbreviated ROF) is always a positive number, however the number may not be a whole number.
	- The maximum number of decimal places ROF may have is 2, decimals beyond this are rounded up.
		- If an ROF bucket has more than 0.95 but less than 1, the bucket is rounded up to 1 when the weapon is next used.
## Using Rate of Fire
- Anytime a weapon is used, the weapon's associated ROF is added to a running sum called the "ROF Bucket".
	- This is done before we check if the ROF bucket is greater than or equal to 1.
	- ROF Buckets are unique to each weapon
	- Note that weapons do not directly attack when used.  
- Anytime a weapon is used and the ROF Bucket of the weapon is greater than or equal to 1, we subtract 1 from the sum and the weapon performs one attack.
- Anytime a creature ends their turn, all weapons with ROF Buckets greater than or equal to 1 have 1 subtracted from them until the associated ROF Bucket is less than 1.
## Rate of Fire Examples
- Below are some common rates of fire and what they translate to in gameplay.

| ROF | Number of Attacks Per Action                                   | Example Weapon      |
| --- | -------------------------------------------------------------- | ------------------- |
| 0.5 | 1 attack every 2 actions.                                      | [[Sniper Rifle]]    |
| 1   | 1 attack every action.                                         | [[Shotgun]]         |
| 1.5 | 1 attack every action, every other action has an extra attack. | [[CR-85 Quickdraw]] |
| 2   | 2 attacks every action.                                        | [[Pistol]]          |
| 3   | 3 attacks every action.                                        | [[AR-6 Baseliner]]  |
| 4   | 4 attacks every action.                                        | [[Submachine Gun]]  |
