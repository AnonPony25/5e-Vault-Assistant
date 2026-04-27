---
NoteIcon: journal
aat-render-enabled: true
fc-category:
  - Event Category 1
fc-display-name:
sessionstatus:
  - Occurred
type: Session Journal
sessionDate: <% tp.date.now("YYYY-MM-DD") %>
sessionNumber:
players: 0
OneLiner:
timelines:
  - journal
tags:
  - journal
  - Category/Journal
sessionRoster: []
sessionAbsent: []
sessionLocation:
sessionXP: 0
sessionGold: 0
---
<%*
const sessionNum = await tp.system.prompt("Session Number (e.g. 42)");
const sessionDate = await tp.system.prompt("Session Date (YYYY-MM-DD)", tp.date.now("YYYY-MM-DD"));
if (sessionNum) {
  await tp.file.rename(`${sessionDate}-Session-${sessionNum.padStart(3,"0")}`);
  setTimeout(() => {
    const f = tp.file.find_tfile(tp.file.path(true));
    if (!f) return;
    app.fileManager.processFrontMatter(f, fm => {
      fm["sessionNumber"] = parseInt(sessionNum);
      fm["sessionDate"] = sessionDate;
    });
  }, 100);
}
-%>

> [!NOTE|div-m] Session <% tp.file.title.split("-Session-")[1] ?? "" %>

> [!column|no-i no-t]
>> [!div-m|no-title]
>> ~~~meta-bind
>> INPUT[select(
>> option(1, Roster),
>> option(2, Overview),
>> option(3, GM Notes),
>> class(tabbed)
>> )]
>> ~~~
>>>[!tabbed-box-maxh]
>>> >[!div-m|no-title]
>>> > ![[#Roster|no-h clean]]
>>>
>>> >[!div-m|no-title]
>>> > ![[#Session Overview|no-h clean]]
>>>
>>> >[!div-m|no-title]
>>> > ![[#GM Notes|no-h clean]]

> [!NOTE|no-title]
> ~~~meta-bind
> INPUT[select(
> option(1, Combat Log),
> option(2, Loot),
> option(3, Quest Updates),
> class(tabbed)
> )]
> ~~~
>>[!tabbed-box-maxh]
>>>[!div-m|no-title]
>>> ![[#Combat Log|no-h clean]]
>>
>>> [!div-m|no-title]
>>> ![[#Loot|no-h clean]]
>>
>>> [!div-m|no-title]
>>> ![[#Quest Updates|no-h clean]]

---
# Roster

**Present:**
`INPUT[inlineListSuggester(optionQuery(#Category/Player)):sessionRoster]`

**Absent:**
`INPUT[inlineListSuggester(optionQuery(#Category/Player)):sessionAbsent]`

# Session Overview

**One-Liner:** `INPUT[text:OneLiner]`

**Location:** `INPUT[suggester(optionQuery(#Category/Hub), optionQuery(#Category/Region)):sessionLocation]`

This is what happened!

# GM Notes

Private notes - secrets, foreshadowing, NPC plans.

# Combat Log

| Encounter | Outcome | XP Awarded |
|-----------|---------|------------|
| - | - | - |

Total XP This Session: `INPUT[number:sessionXP]`

# Loot

Gold This Session: `INPUT[number:sessionGold]` gp

| Item | Recipient | Value |
|------|-----------|-------|
| - | - | - |

# Quest Updates

```dataview
TABLE WITHOUT ID link(file.name) AS "Quest", questStatus AS "Status"
FROM "2-World/Quests"
WHERE contains(questSessionObtained, this.file.link)
SORT file.name ASC
```
