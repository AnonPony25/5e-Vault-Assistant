---
name: 2-world-person
description: Use when creating or editing notes in 2-World/People/. Provides correct frontmatter, Templater prompts, MyContainer wiki-link pattern, tabbed Meta Bind layout, and Dataview child queries.
---

# 2 World Person Skill

## File Location
`2-World/People/<Note Name>.md`

## Required Frontmatter
```yaml
tags:
  - Category/People
MyContainer: []
MyCategory:
obsidianUIMode: preview
```

## Key Fields
char_race, char_status, char_gender, char_age, MyContainer (current location)

## Conventions
- **MyContainer**: Set via `app.fileManager.processFrontMatter` with `setTimeout(..., 100)`.
- **Tabbed layout**: `INPUT[select(..., class(tabbed))]` with `[!tabbed-box-maxh]` nesting.
- **Child queries**: `WHERE contains(MyContainer, this.file.link)`.
- **BUTTON macros**: `BUTTON[button_person]`, `BUTTON[button_quest]`, etc.
