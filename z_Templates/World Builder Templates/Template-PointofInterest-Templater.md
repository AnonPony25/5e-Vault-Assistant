---
tags:
  - Category/PointofInterest
MyContainer: []
MyCategory:
obsidianUIMode: preview
poiType:
poiStatus: Active
---
<%*
const poiName = await tp.system.prompt("Enter Point of Interest Name", tp.file.title);
if (!poiName) return;
await tp.file.rename(poiName);
const regionFiles = tp.app.vault.getMarkdownFiles()
  .filter(f => f.path.startsWith("2-World/Regions/") || f.path.startsWith("2-World/Hubs/"));
const choices = regionFiles.map(f => f.basename);
const values = regionFiles.map(f => f.path);
const chosenPath = await tp.system.suggester(choices, values, true);
if (!chosenPath) return;
const alias = chosenPath.split("/").pop().replace(/\.md$/, "");
const wikiLink = `[[${chosenPath}|${alias}]]`;
const typeOpts = ["Dungeon","Ruin","Wilderness","Landmark","Religious Site","Hidden","Other"];
const chosenType = await tp.system.suggester(typeOpts, typeOpts, true);
setTimeout(() => {
  const f = tp.file.find_tfile(tp.file.path(true));
  if (!f) return;
  app.fileManager.processFrontMatter(f, fm => {
    fm["MyContainer"] = wikiLink;
    if (chosenType) fm["poiType"] = chosenType;
  });
}, 100);
-%>

> [!NOTE|div-m] Parent Region: `INPUT[inlineListSuggester(optionQuery(#Category/Region),optionQuery(#Category/Hub)):MyContainer]`

> [!column|no-i no-t]
>> [!info|no-title] Map
>> ```leaflet
>> id: <% tp.file.title.replace(/ /g,"-") %>-map
>> image: [[poi-placeholder.png]]
>> bounds: [[0,0], [1000, 1000]]
>> height: 400px
>> width: 95%
>> lat: 500
>> long: 500
>> minZoom: -3
>> maxZoom: 1
>> defaultZoom: -2
>> darkmode: false
>> ```
>
>> [!note|no-title] POI Info
>> ~~~meta-bind
>> INPUT[select(
>> option(1, Overview),
>> option(2, Locations),
>> option(3, Encounters),
>> option(4, GM Notes),
>> class(tabbed)
>> )]
>> ~~~
>>>[!tabbed-box-maxh]
>>> >[!div-m|no-title]
>>> > ![[#Overview|no-h clean]]
>>>
>>> >[!div-m|no-title]
>>> > ![[#Locations|no-h clean]]
>>>
>>> >[!div-m|no-title]
>>> > ![[#Encounters|no-h clean]]
>>>
>>> >[!div-m|no-title]
>>> > ![[#GM Notes|no-h clean]]

---
# Overview

Type: `INPUT[inlineSelect(option(Dungeon), option(Ruin), option(Wilderness), option(Landmark), option(Religious Site), option(Hidden), option(Other)):poiType]`

Status: `INPUT[inlineSelect(option(Active), option(Cleared), option(Unknown)):poiStatus]`

Description.

# Locations

| Area | Description | Encounter? |
|------|-------------|------------|
| Area 1 | - | No |

# Encounters

| Encounter | Difficulty | Notes |
|-----------|------------|-------|
| - | - | - |

# GM Notes

Secret info, traps, treasure, read-aloud text.

## People / Creatures Here

```dataview
TABLE WITHOUT ID link(file.name) AS "Name", char_race AS "Race"
FROM "2-World/People"
WHERE contains(MyContainer, this.file.link)
SORT file.name ASC
```
