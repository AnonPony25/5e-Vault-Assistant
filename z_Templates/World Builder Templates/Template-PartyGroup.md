---
tags:
  - Category/Party
obsidianUIMode: preview
partyName:
campaign:
sessionCount: 0
partyLevel: 1
activePlayers: []
inactivePlayers: []
partyQuests: []
partyTreasury: 0
---
<%*
const partyName = await tp.system.prompt("Enter Party Name", tp.file.title);
if (!partyName) return;
await tp.file.rename(partyName);
setTimeout(() => {
  const f = tp.file.find_tfile(tp.file.path(true));
  if (!f) return;
  app.fileManager.processFrontMatter(f, fm => { fm["partyName"] = partyName; });
}, 100);
-%>

> [!NOTE|div-m] Party: `= this.partyName`

> [!column|no-i no-t]
>> [!div-m|no-title]
>> ![[party-placeholder.png]]
>
>> [!div-m|no-title] Party Dashboard
>> ~~~meta-bind
>> INPUT[select(
>> option(1, Roster),
>> option(2, Treasury),
>> option(3, Active Quests),
>> option(4, Notes),
>> class(tabbed)
>> )]
>> ~~~
>>>[!tabbed-box-maxh]
>>> >[!div-m|no-title]
>>> > ![[#Roster|no-h clean]]
>>>
>>> >[!div-m|no-title]
>>> > ![[#Treasury|no-h clean]]
>>>
>>> >[!div-m|no-title]
>>> > ![[#Active Quests|no-h clean]]
>>>
>>> >[!div-m|no-title]
>>> > ![[#Notes|no-h clean]]

---
# Roster

Campaign: `INPUT[inlineSelect(option(Campaign 1), option(Campaign 2)):campaign]`
Party Level: `INPUT[number:partyLevel]`

**Active Players:**
`INPUT[inlineListSuggester(optionQuery(#Category/Player)):activePlayers]`

**Inactive Players:**
`INPUT[inlineListSuggester(optionQuery(#Category/Player)):inactivePlayers]`

```dataview
TABLE WITHOUT ID link(file.name) AS "Character", char_class AS "Class", level AS "Level", char_race AS "Race", char_status AS "Status"
FROM "1-Party"
WHERE contains(tags, "Category/Player") AND Status = "Active"
SORT level DESC
```

# Treasury

Party Gold: `INPUT[number:partyTreasury]` gp

| Item | Value | Source |
|------|-------|--------|
| - | - | - |

# Active Quests

Sessions Played: `INPUT[number:sessionCount]`

`INPUT[inlineListSuggester(optionQuery(#Category/Quest)):partyQuests]`

```dataview
TABLE WITHOUT ID link(file.name) AS "Quest", questStatus AS "Status", questGiver AS "Quest Giver"
FROM "2-World/Quests"
WHERE questStatus != "Complete"
SORT file.name ASC
```

# Notes

General party notes and running observations here.
