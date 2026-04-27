---
obsidianUIMode: preview
cssclasses:
  - json5e-bastion
tags:
  - Category/Bastion
aliases:
  - "Bastion Name"
owner:
bastionLevel: 1
bastionSize: Cramped
bastionFacilities: []
bastionDefenseBonus: 0
---
<%*
const bName = await tp.system.prompt("Bastion Name", tp.file.title);
if (!bName) return;
await tp.file.rename(bName);
const ownerFiles = tp.app.vault.getMarkdownFiles().filter(f => f.path.startsWith("1-Party/"));
const choices = ownerFiles.map(f => f.basename);
const values = ownerFiles.map(f => f.path);
const chosenOwner = await tp.system.suggester(choices, values, false);
setTimeout(() => {
  const f = tp.file.find_tfile(tp.file.path(true));
  if (!f) return;
  app.fileManager.processFrontMatter(f, fm => {
    if (chosenOwner) fm["owner"] = chosenOwner.split("/").pop().replace(/\.md$/,"");
  });
}, 100);
-%>

> [!NOTE|div-m] Owner: `INPUT[suggester(optionQuery(#Category/Player)):owner]`

> [!column|no-i no-t]
>> [!div-m|no-title]
>> ![[bastion-placeholder.png]]
>
>> [!div-m|no-title] Bastion Dashboard
>> ~~~meta-bind
>> INPUT[select(option(1, Overview), option(2, Facilities), option(3, Defense), option(4, GM Notes), class(tabbed))]
>> ~~~
>>>[!tabbed-box-maxh]
>>> >[!div-m|no-title]
>>> > ![[#Overview|no-h clean]]
>>> >[!div-m|no-title]
>>> > ![[#Facilities|no-h clean]]
>>> >[!div-m|no-title]
>>> > ![[#Defense|no-h clean]]
>>> >[!div-m|no-title]
>>> > ![[#GM Notes|no-h clean]]

---
# Overview

**Level:** `INPUT[number:bastionLevel]`
**Size:** `INPUT[inlineSelect(option(Cramped), option(Roomy), option(Vast)):bastionSize]`
**Location:**

Description of this bastion.

# Facilities

`INPUT[inlineListSuggester(option(Arcane Study), option(Armory), option(Barrack), option(Smithy), option(Stable), option(Storehouse), option(Sanctuary), option(Garden), option(Library), option(Trophy Room), option(Workshop)):bastionFacilities]`

| Facility | Level | Description |
|----------|-------|-------------|
| - | - | - |

# Defense

**Defense Bonus:** `INPUT[number:bastionDefenseBonus]`

| Defender | Role | Notes |
|----------|------|-------|
| - | - | - |

# GM Notes

Notes about events or plot hooks tied to this bastion.
