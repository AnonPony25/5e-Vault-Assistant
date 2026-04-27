---
name: 3-mechanics-list
description: Use when creating or editing a D&D 5e list/index file in the 3-Mechanics repository (lists/ folder). These files aggregate optional features, spell lists, or class lists. Provides the correct Obsidian/5etools Markdown structure with json5e-note cssclass and bulleted internal links.
---

# 3-Mechanics List File Template

Use this skill whenever you need to create or modify a file inside `lists/` in the 3-Mechanics vault.

## File Naming Convention

```
list-<list-type>-<source-code>.md
```
Examples: `list-optfeaturetype-ai.md` (Artificer Infusions), `list-spells-classes-wizard.md`

## Full Template

```markdown
---
obsidianUIMode: preview
cssclasses:
- json5e-note
tags:
- ttrpg-cli/compendium/src/5e/{{SOURCE_CODE}}
aliases:
- "{{LIST_TITLE}}"
---
# {{LIST_TITLE}}
*Source: {{SOURCE_FULL}}* 

- [{{ENTRY_1_NAME}}](z_CLI/{{ENTRY_1_PATH}}.md)
- [{{ENTRY_2_NAME}}](z_CLI/{{ENTRY_2_PATH}}.md)
- [{{ENTRY_3_NAME}}](z_CLI/{{ENTRY_3_PATH}}.md)
```

## Field Reference

| Placeholder | Description |
|---|---|
| `{{SOURCE_CODE}}` | Lowercase source abbreviation for the list's source |
| `{{LIST_TITLE}}` | Human-readable title for the list, e.g. `Artificer Infusion`, `Wizard Spells` |
| `{{SOURCE_FULL}}` | Full book name only (no page number required for list files) |
| `{{ENTRY_N_NAME}}` | Display name of the linked entry |
| `{{ENTRY_N_PATH}}` | Full path relative to `z_CLI/`, e.g. `optional-features/homunculus-servant-tce` |

## Common List Types and Paths

| List Type | Path Prefix | Example |
|---|---|---|
| Optional Feature (infusion, invocation, etc.) | `optional-features/` | `list-optfeaturetype-ai.md` |
| Spell class list | `spells/` | `list-spells-classes-wizard.md` |
| Subclass spell list | `spells/` | `list-spells-classes-evoker-xphb.md` |
| Item list | `items/` | `list-items-armor.md` |

## Notes

- `cssclasses` must be `json5e-note` (list files are notes, not their own entity type).
- Entries are sorted alphabetically by name.
- All entries link to their full file using `z_CLI/` prefix paths (without `.md` extension shown here as `.md` is required in the actual link).
- The source line uses the book name only, no page number, since these are aggregate lists.
