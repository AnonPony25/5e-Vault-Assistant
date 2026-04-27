---
tags:
  - Category/Hub
MyContainer: []
MyCategory:
obsidianUIMode: preview
hubType: Town
hubPopulation:
hubLeader:
hubFaction:
---
<%*
const hubName = await tp.system.prompt("Enter Hub Name", tp.file.title);
if (!hubName) return;
await tp.file.rename(hubName);
const regionFiles = tp.app.vault.getMarkdownFiles().filter(f => f.path.startsWith("2-World/Regions/"));
const choices = regionFiles.map(f => f.basename);
const values = regionFiles.map(f => f.path);
const chosenPath = await tp.system.suggester(choices, values, true);
if (!chosenPath) return;
const alias = chosenPath.split("/").pop().replace(/\.md$/, "");
const wikiLink = `[[${chosenPath}|${alias}]]`;
const typeOpts = ["City","Town","Village","Hamlet","Encampment","Keep","Fortress","Stronghold","Other"];
const chosenType = await tp.system.suggester(typeOpts, typeOpts, true);
setTimeout(() => {
  const f = tp.file.find_tfile(tp.file.path(true));
  if (!f) return;
  app.fileManager.processFrontMatter(f, fm => {
    fm["MyContainer"] = wikiLink;
    if (chosenType) fm["hubType"] = chosenType;
  });
}, 100);
-%>

> [!NOTE] Parent Region: `INPUT[inlineListSuggester(optionQuery(#Category/Region)):MyContainer]`

> [!column|no-i no-t]
>> [!info|no-title] Map
>> ```leaflet
>> id: <% tp.file.title.replace(/ /g,"-") %>-hub-map
>> image: [[hub-placeholder.png]]
>> bounds: [[0,0], [2000, 2000]]
>> height: 450px
>> width: 95%
>> lat: 1000
>> long: 1000
>> minZoom: -3
>> maxZoom: 1
>> defaultZoom: -2
>> darkmode: false
>> ```
>
>> [!note|no-title] Hub Details
>> ~~~meta-bind
>> INPUT[select(
>> option(1, General),
>> option(2, Districts),
>> option(3, GM Notes),
>> class(tabbed)
>> )]
>> ~~~
>>>[!tabbed-box-maxh]
>>> >[!div-m|no-title]
>>> > ![[#General|no-h clean]]
>>>
>>> >[!div-m|no-title]
>>> > ![[#Districts|no-h clean]]
>>>
>>> >[!div-m|no-title]
>>> > ![[#GM Notes|no-h clean]]

> [!NOTE|no-title]
> ~~~meta-bind
> INPUT[select(
> option(1, Places),
> option(2, People),
> option(3, Groups),
> option(4, Quests),
> class(tabbed)
> )]
> ~~~
>>[!tabbed-box-maxh]
>>>[!div-m|no-title]
>>> ![[#Places|no-h clean]]
>>
>>> [!div-m|no-title]
>>> ![[#People|no-h clean]]
>>
>>> [!div-m|no-title]
>>> ![[#Groups|no-h clean]]
>>
>>> [!div-m|no-title]
>>> ![[#Quests|no-h clean]]

---
# General

Type: `INPUT[inlineSelect(option(City), option(Town), option(Village), option(Hamlet), option(Encampment), option(Keep), option(Fortress), option(Stronghold), option(Other)):hubType]`

Population: `INPUT[number:hubPopulation]`

Leader: `INPUT[suggester(optionQuery(#Category/People)):hubLeader]`

Dominant Faction: `INPUT[suggester(optionQuery(#Category/Group)):hubFaction]`

Description of this hub.

# Districts

| District | Type | Notes |
|----------|------|-------|
| - | - | - |

# GM Notes

Secrets, rumors, plot hooks tied to this hub.

# Places

`BUTTON[button_place]`

```dataview
TABLE WITHOUT ID link(file.name) AS "Place", MyCategory AS "Type"
FROM "2-World/Places"
WHERE contains(MyContainer, this.file.link)
SORT file.name ASC
```

# People

`BUTTON[button_person]`

```dataview
TABLE WITHOUT ID link(file.name) AS "Name", char_race AS "Race", char_gender AS "Gender", char_status AS "Status"
FROM "2-World/People"
WHERE contains(MyContainer, this.file.link)
SORT file.name ASC
```

# Groups

`BUTTON[button_group]`

```dataview
TABLE WITHOUT ID link(file.name) AS "Group", MyCategory AS "Type"
FROM "2-World/Groups"
WHERE contains(MyContainer, this.file.link)
SORT file.name ASC
```

# Quests

`BUTTON[button_quest]`

```dataview
TABLE WITHOUT ID link(file.name) AS "Quest", questStatus AS "Status", questGiver AS "Quest Giver"
FROM "2-World/Quests"
WHERE contains(MyContainer, this.file.link)
SORT file.name ASC
```
