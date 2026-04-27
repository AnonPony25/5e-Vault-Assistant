---
name: 3-mechanics-optional-feature
description: Use when creating or editing a D&D 5e optional feature file in the 3-Mechanics repository (optional-features/ folder). Optional features include Eldritch Invocations, Fighting Styles, Metamagic, Pact Boons, Artificer Infusions, and similar class-gated choices. Provides the correct Obsidian/5etools Markdown structure with json5e-feat cssclass and optional-feature type tag.
---

# 3-Mechanics Optional Feature File Template

Use this skill whenever you need to create or modify a file inside `optional-features/` in the 3-Mechanics vault.

## File Naming Convention

```
<feature-slug>-<source-code>.md
```
Examples: `agonizing-blast-xphb.md`, `homunculus-servant-tce.md`, `twin-spell-xphb.md`

## Optional Feature Type Tags

| Feature Category | Tag Suffix | Example |
|---|---|---|
| Eldritch Invocation | `ei` | `ttrpg-cli/optional-feature/ei` |
| Fighting Style | `fs` | `ttrpg-cli/optional-feature/fs` |
| Metamagic | `mm` | `ttrpg-cli/optional-feature/mm` |
| Pact Boon | `pb` | `ttrpg-cli/optional-feature/pb` |
| Artificer Infusion | `ai` | `ttrpg-cli/optional-feature/ai` |
| Arcane Shot | `as` | `ttrpg-cli/optional-feature/as` |
| Elemental Discipline | `ed` | `ttrpg-cli/optional-feature/ed` |

## Full Template

```markdown
---
obsidianUIMode: preview
cssclasses:
- json5e-feat
tags:
- ttrpg-cli/compendium/src/5e/{{SOURCE_CODE}}
- ttrpg-cli/optional-feature/{{FEATURE_TYPE}}
aliases:
- "{{NAME}}"
---
# {{NAME}}
*Source: {{SOURCE_FULL}}*  

**Prerequisite**: {{PREREQUISITES}}

{{FEATURE_DESCRIPTION}}

## Repeatable

{{REPEATABLE_TEXT}}
```

## Field Reference

| Placeholder | Description |
|---|---|
| `{{SOURCE_CODE}}` | Lowercase source abbreviation |
| `{{FEATURE_TYPE}}` | Type suffix from table above, e.g. `ei`, `ai`, `mm` |
| `{{NAME}}` | Full display name of the optional feature |
| `{{SOURCE_FULL}}` | Full book title + page |
| `{{PREREQUISITES}}` | Level requirement and any class/ability requirements |
| `{{FEATURE_DESCRIPTION}}` | Mechanical text of the feature, with `z_CLI/` links |
| `{{REPEATABLE_TEXT}}` | Description of how/when the feature can be taken multiple times |

## Notes

- `cssclasses` must be `json5e-feat` (not `json5e-optional-feature`).
- The `ttrpg-cli/optional-feature/{{type}}` tag identifies this as an optional feature vs. a regular feat.
- Omit the `## Repeatable` section entirely if the feature cannot be taken more than once.
- If there is no prerequisite, write `None` or omit the **Prerequisite** line.
- Infusion items that create magic items link to the item using `[Item Name](z_CLI/items/item-slug.md)`.
