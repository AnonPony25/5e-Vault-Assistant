---
name: 2-world-quest
description: Use when creating or editing notes in 2-World/Quests/. Provides correct frontmatter, Templater prompts, MyContainer wiki-link pattern, tabbed Meta Bind layout, and Dataview child queries.
---

# 2 World Quest Skill

## File Location
`2-World/Quests/<Note Name>.md`

## Required Frontmatter
```yaml
tags:
  - Category/Quest
MyContainer: []
MyCategory:
obsidianUIMode: preview
```

## Key Fields
questStatus, questGiver, questSessionObtained, MyContainer (related hub)

## Conventions
- **MyContainer**: Set via `app.fileManager.processFrontMatter` with `setTimeout(..., 100)`.
- **Tabbed layout**: `INPUT[select(..., class(tabbed))]` with `[!tabbed-box-maxh]` nesting.
- **Child queries**: `WHERE contains(MyContainer, this.file.link)`.
- **BUTTON macros**: `BUTTON[button_person]`, `BUTTON[button_quest]`, etc.
