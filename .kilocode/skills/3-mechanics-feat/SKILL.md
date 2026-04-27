---
name: 3-mechanics-feat
description: Use when creating or editing a D&D 5e feat file in the 3-Mechanics repository (feats/ folder). Provides the correct Obsidian/5etools Markdown structure with json5e-feat cssclass, prerequisite line, ability score increase, and named benefit bullets.
---

# 3-Mechanics Feat File Template

Use this skill whenever you need to create or modify a file inside `feats/` in the 3-Mechanics vault.

## File Naming Convention

```
<feat-slug>-<source-code>.md
```
Examples: `actor-xphb.md`, `alert-xphb.md`, `war-caster-phb.md`

## Full Template

```markdown
---
obsidianUIMode: preview
cssclasses:
- json5e-feat
tags:
- ttrpg-cli/compendium/src/5e/{{SOURCE_CODE}}
- ttrpg-cli/feat
aliases:
- "{{NAME}}"
---
# {{NAME}}
*Source: {{SOURCE_FULL}}*  

**Prerequisite**: {{PREREQUISITES}}

{{FEAT_INTRO_DESCRIPTION}}

**Ability Score Increase.** Increase your {{ABILITY}} score by 1, to a maximum of 20.

**{{BENEFIT_1_NAME}}.** {{BENEFIT_1_DESCRIPTION}}

**{{BENEFIT_2_NAME}}.** {{BENEFIT_2_DESCRIPTION}}
```

## Field Reference

| Placeholder | Description |
|---|---|
| `{{SOURCE_CODE}}` | Lowercase source abbreviation |
| `{{NAME}}` | Full display name of the feat |
| `{{SOURCE_FULL}}` | Full book title + page |
| `{{PREREQUISITES}}` | Prerequisite text, e.g. `4th; Charisma 13 or higher` |
| `{{FEAT_INTRO_DESCRIPTION}}` | Optional intro sentence (e.g. "You gain the following benefits.") |
| `{{ABILITY}}` | Ability score name being increased |
| `{{BENEFIT_N_NAME}}` | Bold benefit name |
| `{{BENEFIT_N_DESCRIPTION}}` | Description text for that benefit, with links where applicable |

## Notes

- `cssclasses` must be `json5e-feat`.
- Always include the `ttrpg-cli/feat` tag.
- If a feat has no ASI, omit the **Ability Score Increase** line.
- If there is no prerequisite, use `None` as the value or omit the **Prerequisite** line.
- Use `[Advantage](z_CLI/rules/variant-rules/advantage-xphb.md)` and similar links for rules terms.
- Feats in `optional-features/` that are Eldritch Invocations, Fighting Styles, etc. use the `json5e-feat` cssclass as well but carry a `ttrpg-cli/optional-feature/{{type}}` tag instead of `ttrpg-cli/feat`.
