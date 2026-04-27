---
obsidianUIMode: preview
---
# Party Tracker

## Active Characters

```dataview
TABLE WITHOUT ID link(file.name) AS "Character", char_class AS "Class", level AS "Level", char_race AS "Race", hp AS "HP", max_hp AS "Max HP", ac AS "AC"
FROM "1-Party"
WHERE contains(tags, "Category/Player") AND Status = "Active"
SORT level DESC
```

## Faction Standings

```dataviewjs
const players = dv.pages('"1-Party"').where(p => p.tags && p.tags.some(t => t.includes("Category/Player")));
let rows = [];
for (let p of players) {
  let standings = p.faction_standing ?? {};
  for (let [faction, standing] of Object.entries(standings)) {
    rows.push([dv.fileLink(p.file.path), faction, standing]);
  }
}
dv.table(["Character", "Faction", "Standing"], rows);
```

## Inventory Summary

```dataviewjs
const players = dv.pages('"1-Party"').where(p => p.tags && p.tags.some(t => t.includes("Category/Player")));
let rows = [];
for (let p of players) {
  let items = Array.isArray(p.char_items) ? p.char_items : (p.char_items ? [p.char_items] : []);
  rows.push([dv.fileLink(p.file.path), items.length, items.join(", ")]);
}
dv.table(["Character", "Item Count", "Items"], rows);
```
