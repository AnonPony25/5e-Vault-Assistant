---
name: 3-mechanics-race
description: Use when creating or editing a D&D 5e race or species file in the 3-Mechanics repository (races/ folder). Provides the correct Obsidian/5etools Markdown structure with json5e-race cssclass, ability scores, size, speed, spellcasting ability, and trait sections.
---

# 3-Mechanics Race File Template

Use this skill whenever you need to create or modify a file inside `races/` in the 3-Mechanics vault.

## File Naming Convention

```
<race-slug>-<source-code>.md
```
Examples: `aasimar-xphb.md`, `aarakocra-mpmm.md`, `dwarf-hill-phb.md`

## Full Template

```markdown
---
obsidianUIMode: preview
cssclasses:
- json5e-race
tags:
- ttrpg-cli/compendium/src/5e/{{SOURCE_CODE}}
- ttrpg-cli/race/{{RACE_SLUG}}
aliases:
- "{{NAME}}"
---
# {{NAME}}
*Source: {{SOURCE_FULL}}*  

- **Ability Scores**: {{ABILITY_SCORES}}
- **Type**: {{TYPE}}
- **Size**: {{SIZE}}
- **Speed**: {{SPEED}}
- **Spellcasting**: {{SPELLCASTING_ABILITY}}

## Traits

### {{TRAIT_1_NAME}}

{{TRAIT_1_DESCRIPTION}}

### {{TRAIT_2_NAME}}

{{TRAIT_2_DESCRIPTION}}

### {{TRAIT_3_NAME}}

{{TRAIT_3_DESCRIPTION}}
```

## Field Reference

| Placeholder | Description |
|---|---|
| `{{SOURCE_CODE}}` | Lowercase source abbreviation |
| `{{RACE_SLUG}}` | Lowercase race name slug, e.g. `aasimar`, `aarakocra`, `dwarf-hill` |
| `{{NAME}}` | Full display name |
| `{{SOURCE_FULL}}` | Full book title + page |
| `{{ABILITY_SCORES}}` | Ability score grants; use `None` for 2024 free-choice rules |
| `{{TYPE}}` | Creature type, typically `humanoid` |
| `{{SIZE}}` | Size option(s), e.g. `Small or Medium`, `Medium` |
| `{{SPEED}}` | Base walking speed, e.g. `30 ft.`; include swim/fly speed if applicable |
| `{{SPELLCASTING_ABILITY}}` | Spellcasting ability for racial spells; omit line if none |
| `{{TRAIT_N_NAME}}` | Name of the racial trait |
| `{{TRAIT_N_DESCRIPTION}}` | Full mechanical description with links |

## Notes

- `cssclasses` must be `json5e-race`.
- Omit `**Spellcasting**` line entirely if the race grants no spells.
- For subraces (e.g., `dwarf-hill`), the parent race name appears in the heading and subraces are handled in separate files with `ttrpg-cli/race/dwarf-hill` tag.
- `[Resistance](z_CLI/rules/variant-rules/resistance-xphb.md)` and similar rules terms must be linked.
- For 2024 PHB races with free ASI (Ability Scores: None), still include the `**Ability Scores**` line.
