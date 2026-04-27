---
obsidianUIMode: preview
---
# Mechanics Index

## Spells

```dataview
TABLE WITHOUT ID link(file.name) AS "Spell", file.folder AS "School"
FROM "3-Mechanics/spells"
SORT file.name ASC
```

## Items

```dataview
TABLE WITHOUT ID link(file.name) AS "Item"
FROM "3-Mechanics/items"
SORT file.name ASC
```

## Bestiary

```dataview
TABLE WITHOUT ID link(file.name) AS "Creature", file.folder AS "Type"
FROM "3-Mechanics/bestiary"
WHERE file.name != "bestiary"
SORT file.name ASC
```

## Feats

```dataview
TABLE WITHOUT ID link(file.name) AS "Feat", featCategory AS "Category", featPrerequisite AS "Prereq"
FROM "3-Mechanics/feats"
SORT file.name ASC
```

## Classes

```dataview
TABLE WITHOUT ID link(file.name) AS "Class"
FROM "3-Mechanics/classes"
SORT file.name ASC
```

## Deities

```dataview
TABLE WITHOUT ID link(file.name) AS "Deity", deityAlignment AS "Alignment", deityDomain AS "Domains", deityPantheon AS "Pantheon"
FROM "3-Mechanics/deities"
SORT file.name ASC
```
