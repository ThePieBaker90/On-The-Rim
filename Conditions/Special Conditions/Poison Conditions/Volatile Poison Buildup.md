---
tags:
  - Condition
  - Negative-Condition
---
- Volatile Poison Buildup is measured in different levels.
	- An effect can give a creature one or more levels of volatile poison buildup, as specified in the effect’s description. 
	- Creatures who are immune to poison damage are not affected by this condition.
	- If a creature already suffers from volatile poison buildup and suffers another effect that causes volatile poison buildup, its current level of  volatile poison buildup increases by the amount specified in the effect’s description.
	- If a creature already suffers from [[Poison Buildup]] and suffers another effect that causes volatile poison buildup, all levels of [[Poison Buildup]] become volatile poison buildup.
- Volatile Poison Buildup dissipates on its own, 1 level every time the creature receives the effects of poison buildup.
- Volatile Poison Buildup is not capped.

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
| 15                   | 22 poison damage per turn.                             | 1                            |



