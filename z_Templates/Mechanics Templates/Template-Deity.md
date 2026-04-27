---
obsidianUIMode: preview
cssclasses:
  - json5e-deity
tags:
  - ttrpg-cli/compendium/src/5e/phb
  - Category/Deity
aliases:
  - "Deity Name"
deityAlignment:
deityDomain: []
deitySex:
deityPantheon:
deityWorshippers:
deitySymbol:
deityPortfolio:
---
<%*
const dName = await tp.system.prompt("Deity Name", tp.file.title);
if (!dName) return;
await tp.file.rename(dName);
-%>

> [!NOTE|div-m] Deity: `= this.file.name`

> [!column|no-i no-t]
>> [!div-m|no-title]
>> ![[deity-placeholder.png]]
>
>> [!div-m|no-title] Deity Info
>> ~~~meta-bind
>> INPUT[select(option(1, Overview), option(2, Worship), option(3, GM Notes), class(tabbed))]
>> ~~~
>>>[!tabbed-box-maxh]
>>> >[!div-m|no-title]
>>> > ![[#Overview|no-h clean]]
>>> >[!div-m|no-title]
>>> > ![[#Worship|no-h clean]]
>>> >[!div-m|no-title]
>>> > ![[#GM Notes|no-h clean]]

---
# Overview

**Alignment:** `INPUT[inlineSelect(option(LG), option(NG), option(CG), option(LN), option(TN), option(CN), option(LE), option(NE), option(CE)):deityAlignment]`
**Gender:** `INPUT[inlineSelect(option(Male), option(Female), option(Non-binary), option(None)):deitySex]`
**Pantheon:** `INPUT[text:deityPantheon]`
**Portfolio:** `INPUT[text:deityPortfolio]`
**Symbol:** `INPUT[text:deitySymbol]`

*Source: <!-- source -->*

<!-- Deity description -->

# Worship

**Domains:** `INPUT[inlineListSuggester(option(Life), option(Light), option(Tempest), option(Knowledge), option(Nature), option(Trickery), option(War), option(Death), option(Forge), option(Grave), option(Order), option(Peace), option(Twilight)):deityDomain]`

**Worshippers:** `INPUT[text:deityWorshippers]`

**Holy Days:**

**Tenets:**

# GM Notes

Notes on this deity's influence in your campaign.

## Connected Groups

```dataview
TABLE WITHOUT ID link(file.name) AS "Group", MyCategory AS "Type"
FROM "2-World/Groups"
WHERE contains(faction, this.file.name)
SORT file.name ASC
```
