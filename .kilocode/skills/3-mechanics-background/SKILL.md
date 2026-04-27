---
name: 3-mechanics-background
description: Use when creating or editing a D&D 5e background file in the 3-Mechanics repository (backgrounds/ folder). Provides the correct Obsidian/5etools Markdown structure, frontmatter fields, cssclass, tags, and content layout for background entries.
---

# 3-Mechanics Background File Template

Use this skill whenever you need to create or modify a file inside `backgrounds/` in the 3-Mechanics vault.

## File Naming Convention

```
<background-slug>-<source-code>.md
```
Examples: `acolyte-xphb.md`, `sage-phb.md`

## Full Template

```markdown
---
obsidianUIMode: preview
cssclasses:
- json5e-background
tags:
- ttrpg-cli/background
- ttrpg-cli/compendium/src/5e/{{SOURCE_CODE}}
aliases:
- "{{NAME}}"
---
# {{NAME}}
*Source: {{SOURCE_FULL}}*  

**Ability Score Increase**: {{ABILITY_SCORE_INCREASE_DESCRIPTION}}

- **Ability Scores.** {{ABILITY_SCORES}}
- **Feat.** [{{FEAT_NAME}}](z_CLI/feats/{{FEAT_SLUG}}.md)
- **Skill Proficiencies.** [{{SKILL_1}}](z_CLI/rules/skills.md#{{SKILL_1}}), [{{SKILL_2}}](z_CLI/rules/skills.md#{{SKILL_2}})
- **Tool Proficiency.** [{{TOOL_NAME}}](z_CLI/items/{{TOOL_SLUG}}.md)
- **Equipment.** Choose A or B: (A) {{EQUIPMENT_A}}; or (B) {{EQUIPMENT_B}}

{{BACKGROUND_DESCRIPTION}}
```

## Field Reference

| Placeholder | Description |
|---|---|
| `{{SOURCE_CODE}}` | Lowercase source abbreviation, e.g. `xphb`, `phb`, `tce` |
| `{{NAME}}` | Full display name of the background |
| `{{SOURCE_FULL}}` | Full book title + page, e.g. `Player's Handbook (2024) p. 178` |
| `{{ABILITY_SCORE_INCREASE_DESCRIPTION}}` | Human-readable description of the ASI options |
| `{{ABILITY_SCORES}}` | Comma-separated ability score names eligible for increase |
| `{{FEAT_SLUG}}` | Kebab-case slug of the associated feat |
| `{{SKILL_1}}`, `{{SKILL_2}}` | Skill proficiency names (capitalized) |
| `{{TOOL_SLUG}}` | Kebab-case slug for tool proficiency item link |
| `{{EQUIPMENT_A}}` / `{{EQUIPMENT_B}}` | Equipment option text with item links |
| `{{BACKGROUND_DESCRIPTION}}` | Flavour paragraph describing the background |

## Notes

- `obsidianUIMode: preview` is always set.
- The `cssclasses` value must be `json5e-background`.
- Tag format follows `ttrpg-cli/compendium/src/5e/<source>`.
- Item and feat links always use `z_CLI/` prefix paths.
- Omit bullet points that don't apply (e.g., no tool proficiency → remove that line).
