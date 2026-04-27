---
obsidianUIMode: preview
---
# World Overview

## All Regions

```dataview
TABLE WITHOUT ID link(file.name) AS "Region"
FROM "2-World/Regions"
SORT file.name ASC
```

## All Hubs

```dataview
TABLE WITHOUT ID link(file.name) AS "Hub", MyCategory AS "Type", MyContainer AS "Region"
FROM "2-World/Hubs"
SORT file.name ASC
```

## All People

```dataview
TABLE WITHOUT ID link(file.name) AS "Person", char_race AS "Race", char_status AS "Status", char_gender AS "Gender", MyContainer AS "Location"
FROM "2-World/People"
SORT char_status ASC, file.name ASC
```

## All Groups

```dataview
TABLE WITHOUT ID link(file.name) AS "Group", MyCategory AS "Type", leader AS "Leader", MyContainer AS "Home"
FROM "2-World/Groups"
SORT file.name ASC
```

## All Quests

```dataview
TABLE WITHOUT ID link(file.name) AS "Quest", questStatus AS "Status", questGiver AS "Giver", questSessionObtained AS "Session"
FROM "2-World/Quests"
SORT questStatus ASC, file.name ASC
```
