---
name: 2-world-hub
description: Use when creating or editing notes in 2-World/Hubs/. Provides correct frontmatter, Templater prompts, MyContainer wiki-link pattern, tabbed Meta Bind layout, and Dataview child queries.
---

# 2 World Hub Skill

## File Location
`2-World/Hubs/<Note Name>.md`

## Required Frontmatter
```yaml
tags:
  - Category/Hub
MyContainer: []
MyCategory:
obsidianUIMode: preview
```

## Key Fields
hubType, hubPopulation, hubLeader, hubFaction, MyContainer (parent region)

## Conventions
- **MyContainer**: Set via `app.fileManager.processFrontMatter` with `setTimeout(..., 100)`.
- **Tabbed layout**: `INPUT[select(..., class(tabbed))]` with `[!tabbed-box-maxh]` nesting.
- **Child queries**: `WHERE contains(MyContainer, this.file.link)`.
- **BUTTON macros**: `BUTTON[button_person]`, `BUTTON[button_quest]`, etc.
