---
name: 3-mechanics-bastion
description: Use when creating or editing a D&D 5e bastion facility file in the 3-Mechanics repository (bastions/ folder). Provides the correct Obsidian/5etools Markdown structure, frontmatter, and section layout for bastion entries including prerequisites, space, hirelings, orders, and craft options.
---

# 3-Mechanics Bastion File Template

Use this skill whenever you need to create or modify a file inside `bastions/` in the 3-Mechanics vault.

## File Naming Convention

```
<facility-slug>-<source-code>.md
```
Examples: `arcane-study.md`, `armory.md`, `barrack.md`

## Full Template

```markdown
---
obsidianUIMode: preview
cssclasses:
- json5e-bastion
tags:
- ttrpg-cli/bastion
- ttrpg-cli/compendium/src/5e/{{SOURCE_CODE}}
aliases:
- "{{NAME}}"
---
# {{NAME}}
*Level {{LEVEL}} Bastion facility*  

- **Prerequisites**: {{PREREQUISITES}}
- **Space**: {{SPACE}} ({{SPACE_SQ}} sq)
- **Hirelings**: {{HIRELINGS}}
- **Order**: {{ORDER}}

{{FACILITY_DESCRIPTION}}

## {{SPECIAL_FEATURE_NAME}}

{{SPECIAL_FEATURE_DESCRIPTION}}

## Craft Options

When you issue the "Craft" order to this facility, choose one of the following options:

- **Craft.** {{CRAFT_OPTION_1}}
- **Craft.** {{CRAFT_OPTION_2}}

*Source: {{SOURCE_FULL}}*
```

## Field Reference

| Placeholder | Description |
|---|---|
| `{{SOURCE_CODE}}` | Lowercase source abbreviation, e.g. `xdmg` |
| `{{NAME}}` | Display name of the facility |
| `{{LEVEL}}` | Minimum character level required, e.g. `5` |
| `{{PREREQUISITES}}` | Prerequisite text (abilities, spells, or class features required) |
| `{{SPACE}}` | Space tier: `Cramped`, `Roomy`, or `Vast` |
| `{{SPACE_SQ}}` | Square footage number |
| `{{HIRELINGS}}` | Number of hirelings assigned |
| `{{ORDER}}` | The bastion order type, e.g. `craft`, `empower`, `trade` |
| `{{SPECIAL_FEATURE_NAME}}` | Name of the passive or special feature section |
| `{{CRAFT_OPTION_N}}` | Text for each craft option with item links |
| `{{SOURCE_FULL}}` | Full book title + page |

## Notes

- `cssclasses` must be `json5e-bastion`.
- The source line at the bottom uses italic `*Source: ...*` format.
- Omit the "Craft Options" section entirely if the facility's order is not `craft`.
- Use `[Item Name](z_CLI/items/item-slug.md)` for all linked items.
- Use `[Spell Name](z_CLI/spells/spell-slug.md)` for any linked spells.
