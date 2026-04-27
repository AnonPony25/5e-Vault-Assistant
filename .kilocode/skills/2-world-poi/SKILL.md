---
name: 2-world-poi
description: Use when creating or editing notes in 2-World/Points of Interest/. Provides correct frontmatter, Templater prompts, MyContainer wiki-link pattern, tabbed Meta Bind layout, and Dataview child queries.
---

# 2 World Poi Skill

## File Location
`2-World/Points of Interest/<Note Name>.md`

## Required Frontmatter
```yaml
tags:
  - Category/PointofInterest
MyContainer: []
MyCategory:
obsidianUIMode: preview
```

## Key Fields
poiType, poiStatus, MyContainer (parent region/hub)

## Conventions
- **MyContainer**: Set via `app.fileManager.processFrontMatter` with `setTimeout(..., 100)`.
- **Tabbed layout**: `INPUT[select(..., class(tabbed))]` with `[!tabbed-box-maxh]` nesting.
- **Child queries**: `WHERE contains(MyContainer, this.file.link)`.
- **BUTTON macros**: `BUTTON[button_person]`, `BUTTON[button_quest]`, etc.
