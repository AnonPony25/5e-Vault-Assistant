---
name: 2-world-group
description: Use when creating or editing notes in 2-World/Groups/. Provides correct frontmatter, Templater prompts, MyContainer wiki-link pattern, tabbed Meta Bind layout, and Dataview child queries.
---

# 2 World Group Skill

## File Location
`2-World/Groups/<Note Name>.md`

## Required Frontmatter
```yaml
tags:
  - Category/Group
MyContainer: []
MyCategory:
obsidianUIMode: preview
```

## Key Fields
leader, officers, MyCategory (faction type), MyContainer (home hub/region)

## Conventions
- **MyContainer**: Set via `app.fileManager.processFrontMatter` with `setTimeout(..., 100)`.
- **Tabbed layout**: `INPUT[select(..., class(tabbed))]` with `[!tabbed-box-maxh]` nesting.
- **Child queries**: `WHERE contains(MyContainer, this.file.link)`.
- **BUTTON macros**: `BUTTON[button_person]`, `BUTTON[button_quest]`, etc.
