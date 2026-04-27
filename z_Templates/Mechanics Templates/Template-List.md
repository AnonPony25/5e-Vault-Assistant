---
obsidianUIMode: preview
cssclasses:
  - json5e-list
tags:
  - Category/List
aliases:
  - "List Name"
listType:
---

# List Name

*Source: <!-- source -->*

## Entries

```dataview
TABLE WITHOUT ID link(file.name) AS "Entry", file.folder AS "Category"
FROM "3-Mechanics/<!-- folder -->"
WHERE contains(tags, "<!-- tag -->")
SORT file.name ASC
```
