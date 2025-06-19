---
tags:
  - Info
---
Every creature, vehicle, construct, etc. that can be targeted has an Armor Value (AV) separate from its Armor Class (AC). While the AC describes the difficulty of hitting the target, the AV represents the difficulty of penetrating its protection.
All weapons, ammunition, spells, or anything else that may cause damage has an Armor Penetration (AP). Some damage sources may ignore armor value completely. 
AV/AP ranges on a scale of 0 to 9.

| Armor Value | Example Armor             | Example Attack |
| ----------- | ------------------------- | -------------- |
| 0           | No Armor                  |                |
| 1           | Clothing                  |                |
| 2           | Light Personal Armor      |                |
| 3           | Medium Personal Armor     |                |
| 4           | Heavy Personal Armor      |                |
| 5           | Armored Car               |                |
| 6           | Mech                      |                |
| 7           | Armored Personnel Carrier |                |
| 8           | Infantry Fighting Vehicle |                |
| 9           | Battle Tank               |                |


Larger targets may have multiple armor values, for example on front/sides/rear. Larger targets may also have multiple modules of varying AV and AC, destroying which may disable the target in various ways.

When attempting to damage a target with an AV exceeding the source's AP, a decrease to hit rolls is applied due to the difficulty of penetrating the target. 

This decrease is modeled by 2^n where n is AV-AP, the result is then rounded down. Below is a table of possible values.

| n   | Hit Modifier |
| --- | ------------ |
| ≤ 0 | None         |
| 1   | -1           |
| 2   | -2           |
| 3   | -4           |
| 4   | -8           |
| 5   | -16          |
| 6   | -32          |
| 7   | -64          |
| 8   | -128         |
| 9   | -256         |

