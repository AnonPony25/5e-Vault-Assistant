---
tags:
  - Category/Place
MyContainer: []
MyCategory:
obsidianUIMode: preview
---
<%*
const placeName = await tp.system.prompt("Enter Place Name", tp.file.title);
if (!placeName) return;
await tp.file.rename(placeName);
const hubFiles = tp.app.vault.getMarkdownFiles()
  .filter(f => f.path.startsWith("2-World/Hubs/") || f.path.startsWith("2-World/Points of Interest/"));
const choices = hubFiles.map(f => f.basename);
const values = hubFiles.map(f => f.path);
const chosenPath = await tp.system.suggester(choices, values, true);
if (!chosenPath) return;
const alias = chosenPath.split("/").pop().replace(/\.md$/, "");
const wikiLink = `[[${chosenPath}|${alias}]]`;
const catOptions = ["Commerce","Agriculture","Military","Philosophy","Industrial","Nesting","Government","Other"];
const chosenCat = await tp.system.suggester(catOptions, catOptions, true);
setTimeout(() => {
  const f = tp.file.find_tfile(tp.file.path(true));
  if (!f) return;
  app.fileManager.processFrontMatter(f, fm => {
    fm["MyContainer"] = wikiLink;
    if (chosenCat) fm["MyCategory"] = chosenCat;
  });
}, 100);
-%>

> [!NOTE|div-m] Parent Hub: `INPUT[inlineListSuggester(optionQuery(#Category/Hub),optionQuery(#Category/PointofInterest)):MyContainer]`

> [!column|no-i no-t]
>> [!div-m|no-title]
>> ![[place-placeholder.png]]
>
>> [!div-m|no-title] Place Name
>> ~~~meta-bind
>> INPUT[select(
>> option(1, Overview),
>> option(2, Details),
>> option(3, GM Notes),
>> class(tabbed)
>> )]
>> ~~~
>>>[!tabbed-box-maxh]
>>> >[!div-m|no-title]
>>> > ![[#Overview|no-h clean]]
>>>
>>> >[!div-m|no-title]
>>> > ![[#Details|no-h clean]]
>>>
>>> >[!div-m|no-title]
>>> > ![[#GM Notes|no-h clean]]

---
# Overview

Category: `INPUT[inlineSelect(option(Commerce), option(Agriculture), option(Military), option(Philosophy), option(Industrial), option(Nesting), option(Government), option(Other)):MyCategory]`

Description here.

# Details

**Owner/Operator:**
**Hours / Availability:**
**Notable Features:**

# GM Notes

Secret notes about this place.

## NPCs Here

`BUTTON[button_person]`

```dataview
TABLE WITHOUT ID link(file.name) AS "Name", char_race AS "Race", char_gender AS "Gender"
FROM "2-World/People"
WHERE contains(MyContainer, this.file.link)
SORT file.name ASC
```
