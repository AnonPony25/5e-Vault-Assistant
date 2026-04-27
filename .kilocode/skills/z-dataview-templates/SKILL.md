---
name: z-dataview-templates
description: Use when creating Dataview query files in z_Templates/3_Dataview Templates/. Covers DQL and DataviewJS patterns for this vault's folder/tag/field structure.
---

# Dataview Templates Skill

## DQL Table Pattern
```dataview
TABLE WITHOUT ID link(file.name) AS "Label", field AS "Column"
FROM "Folder/Path"
WHERE condition
SORT field ASC
```

## DataviewJS Pattern
```dataviewjs
const pages = dv.pages('"Folder/Path"');
dv.table(["Col1", "Col2"],
  pages.map(p => [dv.fileLink(p.file.path), p.field ?? "-"])
);
```

## Vault Folder Reference

| Folder | Tag | Key Fields |
|--------|-----|-----------|
| `1-Party/` | `Category/Player` | `level`, `char_class`, `char_race`, `hp`, `ac`, `Status` |
| `1-Session Journals/` | `Category/Journal` | `sessionDate`, `OneLiner`, `sessionRoster` |
| `2-World/Regions/` | `Category/Region` | `MyContainer` |
| `2-World/Hubs/` | `Category/Hub` | `MyContainer`, `hubType`, `hubPopulation` |
| `2-World/People/` | `Category/People` | `MyContainer`, `char_race`, `char_status` |
| `2-World/Groups/` | `Category/Group` | `MyContainer`, `MyCategory`, `leader` |
| `2-World/Quests/` | `Category/Quest` | `questStatus`, `questGiver`, `questSessionObtained` |
| `2-World/Places/` | `Category/Place` | `MyContainer`, `MyCategory` |
| `2-World/Points of Interest/` | `Category/PointofInterest` | `MyContainer`, `poiType` |
| `3-Mechanics/items/` | `Category/Item` | `cost`, `weight` |
| `3-Mechanics/bestiary/` | `ttrpg-cli/monster/*` | `ac`, `hp`, `cr` |

## Tips
- Use `TABLE WITHOUT ID` to suppress default File column.
- Use `contains(field, this.file.link)` for bidirectional link arrays.
