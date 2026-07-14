---
tags:
- tags_needed
---

## General Description
Most projectile weapons have some amount of recoil, which makes rapid follow-up attacks on a target more difficult. More powerful, more compact, less ergonomic, and one-handed weapons typically have higher recoil.

## Mechanics
- A weapon's recoil should be specified on its page. It is always a non-negative number, typically a positive integer. Fractional of zero recoil values are possible but not typical.
- For each sucessive round after the first within an attack, the hit roll result is reduced by the value of the recoil.
  - Recoil only applies within single attack action- the recoil counter resets to 0 once that attack is resolved.
- Recoil can be modified by weapon modifications and attachments as well as other sources.
- If a two-handed weapon is used in one hand, its recoil is doubled.
- Even weapons with only single-shot fire modes should have a recoil value- certain abilities may allow the user to use single-shot fire modes multiple times within one action, and some effects or mechanics may need to reference the recoil of a weapon.
## Example
- An attack is made with a rifle with its Burst:3 fire mode
- The roll result is a 16
- The recoil value is 2
- For the first round in the three-round burst, the effective hit roll is 16
- For the second, 16-2=14
- For the third, 16-2-2=12
- If the target's HC is 13, the first two round hit and the third misses
