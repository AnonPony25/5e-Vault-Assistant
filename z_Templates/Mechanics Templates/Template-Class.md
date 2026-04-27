---
obsidianUIMode: preview
cssclasses:
  - json5e-class
tags:
  - ttrpg-cli/compendium/src/5e/phb
  - Category/Class
aliases:
  - "Class Name"
---

# Class Name

*Source: <!-- source -->*

## Class Features

### Hit Points

**Hit Dice:** 1dX per level
**Hit Points at 1st Level:** X + CON modifier
**Hit Points at Higher Levels:** 1dX (or avg) + CON modifier per level after 1st

### Proficiencies

**Armor:** <!-- armor -->
**Weapons:** <!-- weapons -->
**Tools:** <!-- tools -->
**Saving Throws:** <!-- saves -->
**Skills:** Choose N from <!-- list -->

### Equipment

<!-- starting gear -->

## Class Table

| Level | Prof. Bonus | Features |
|-------|:-----------:|---------|
| 1st | +2 | <!-- features --> |
| 2nd | +2 | <!-- features --> |
| 3rd | +2 | <!-- features --> |
| 4th | +2 | Ability Score Improvement |
| 5th | +3 | <!-- features --> |

## Features

### Feature Name

<!-- Feature description -->

## Subclasses

```dataview
TABLE WITHOUT ID link(file.name) AS "Subclass"
FROM "3-Mechanics/classes"
WHERE contains(file.name, this.file.name) AND file.name != this.file.name
SORT file.name ASC
```
