---
tags:
  - Property
  - Grappling-Hook
---
A piece of armor that has the grappling hook property grants the wearer the ability to shoot a grappling hook as an action. The grappling hook must be reloaded after each shot, reloading takes an action. The grappling hook has a range of 80ft and has different behavior depending on what it collides with:
*** 
If the grappling hook is shot at a surface, the wearer will be pulled towards the surface. The surface takes 2d4 piercing damage because of this.
***
If the grappling hook is shot at a creature, the creature will take 2d4 piercing damage upon a successful hit. Upon a miss, the grappling hook will land past the creature. When a creature is “hooked” it and the wearer will be pulled towards each other. The creature’s relativity in size effect the amount each creature is pulled towards each other (See the table below)

| Size Relativity | Wearer Distance | Hooked Distance |
| --------------- | --------------- | --------------- |
| <= -3           | 0x              | 1x              |
| -2              | 0.125x          | 0.875x          |
| -1              | 0.25x           | 0.75x           |
| 0               | 0.5x            | 0.5x            |
| +1              | 0.75x           | 0.25x           |
| +2              | 0.875x          | 0.125x          |
| >= +3           | 1x              | 0x              |
***
To find size relativity you must take both creatures sizes and find the corresponding size numbers on the table below:

| Size       | Size # |
| ---------- | ------ |
| Tiny       | 1      |
| Small      | 2      |
| Medium     | 3      |
| Large      | 4      |
| Huge       | 5      |
| Gargantuan | 6      |

You then subtract the wearer's size number from the hooked creature's size number. The result is the size relativity.
