---
tags:
  - Condition
  - Negative-Condition
---
- Volatile poison buildup always has an indefinite duration.
- Volatile poison buildup may stack.
- When a creature has one or more levels of volatile poison buildup, they suffer the following effects:
	- All levels of [[Poison Buildup]] on them become [[Volatile Poison Buildup]].
	- They take 1.5 damage per level of volatile poison buildup they have, per tun, rounded down.
	- When they take damage from this condition, they lose 1 level of volatile poison buildup.
- Creatures who are immune to poison damage are immune to this condition.

| Poison Buildup Level | Effects                                                | Overall Damage               |
| -------------------- | ------------------------------------------------------ | ---------------------------- |
| {Level}              | {$Level * 1.5$} poison damage per turn. (Rounded down) | $$\sum_{i=1}^{level} i*1.5$$ |
| 1                    | 1 poison damage per turn.                              | 1                            |
| 2                    | 3 poison damage per turn.                              | 4                            |
| 3                    | 4 poison damage per turn.                              | 8                            |
| 4                    | 6 poison damage per turn.                              | 14                           |
| 5                    | 7 poison damage per turn.                              | 21                           |
| 6                    | 9 poison damage per turn.                              | 30                           |
| 7                    | 10 poison damage per turn.                             | 40                           |
| 8                    | 12 poison damage per turn.                             | 52                           |
| 9                    | 13 poison damage per turn.                             | 65                           |
| 10                   | 15 poison damage per turn.                             | 80                           |
| 11                   | 16 poison damage per turn.                             | 96                           |
| 12                   | 18 poison damage per turn.                             | 114                          |
| 13                   | 19 poison damage per turn.                             | 133                          |
| 14                   | 21 poison damage per turn.                             | 154                          |
| 15                   | 22 poison damage per turn.                             | 176                          |



