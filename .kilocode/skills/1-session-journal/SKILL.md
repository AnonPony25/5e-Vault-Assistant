---
name: 1-session-journal
description: Use when creating or editing a session journal in 1-Session Journals/. Covers fc-calendar fields, aat-render-enabled, timelines, roster inputs, combat log, loot, and quest updates.
---

# 1-Session Journal Skill

## File Naming
`YYYY-MM-DD-Session-NNN.md` (e.g. 2025-03-14-Session-042.md)

## Required Frontmatter
```yaml
NoteIcon: journal
aat-render-enabled: true
fc-category:
  - Event Category 1
sessionstatus:
  - Occurred
type: Session Journal
sessionDate: YYYY-MM-DD
sessionNumber: 42
players: 4
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
```

## Sections
- **Roster** - inlineListSuggester for Category/Player
- **Session Overview** - OneLiner, location suggester, narrative
- **GM Notes** - collapsible private callout
- **Combat Log** - encounter/outcome/XP table
- **Loot** - item/recipient/value table + sessionGold
- **Quest Updates** - dataview filtering by questSessionObtained
