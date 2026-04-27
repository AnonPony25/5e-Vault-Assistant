---
name: 3-mechanics-deity
description: Use when creating or editing a D&D 5e deity file in the 3-Mechanics repository (deities/ folder). Provides the correct Obsidian/5etools Markdown structure with json5e-deity cssclass, pantheon tag, domain tags, and deity stat block fields.
---

# 3-Mechanics Deity File Template

Use this skill whenever you need to create or modify a file inside `deities/` in the 3-Mechanics vault.

## File Naming Convention

```
<pantheon-slug>-<deity-slug>.md
```
Examples: `celtic-arawn.md`, `greek-zeus.md`, `forgotten-realms-tyr.md`

## Full Template

```markdown
---
obsidianUIMode: preview
cssclasses:
- json5e-deity
tags:
- ttrpg-cli/compendium/src/5e/{{SOURCE_CODE}}
- ttrpg-cli/deity/{{PANTHEON_SLUG}}
- ttrpg-cli/domain/{{DOMAIN_1_SLUG}}
- ttrpg-cli/domain/{{DOMAIN_2_SLUG}}
aliases:
- "{{NAME}}"
---
# {{NAME}}
*Source: {{SOURCE_FULL}}*  

- **Alignment**: {{ALIGNMENT}}
- **Domains**: {{DOMAINS}}
- **Pantheon**: {{PANTHEON}}
- **Symbol**: {{SYMBOL}}

{{DEITY_DESCRIPTION}}
```

## Field Reference

| Placeholder | Description |
|---|---|
| `{{SOURCE_CODE}}` | Lowercase source abbreviation, e.g. `phb`, `xphb`, `dmg` |
| `{{PANTHEON_SLUG}}` | Lowercase pantheon name, e.g. `celtic`, `greek`, `forgotten-realms` |
| `{{DOMAIN_N_SLUG}}` | Lowercase domain name, e.g. `life`, `death`, `war`, `knowledge` |
| `{{NAME}}` | Full name of the deity |
| `{{SOURCE_FULL}}` | Full book title + page |
| `{{ALIGNMENT}}` | Full alignment string, e.g. `Neutral Evil`, `Lawful Good` |
| `{{DOMAINS}}` | Comma-separated domain names, e.g. `Life, Death` |
| `{{PANTHEON}}` | Display name of the pantheon |
| `{{SYMBOL}}` | Brief description of the deity's holy symbol |
| `{{DEITY_DESCRIPTION}}` | Optional lore paragraph(s) about the deity |

## Notes

- `cssclasses` must be `json5e-deity`.
- Add one `ttrpg-cli/domain/{{slug}}` tag per domain the deity offers.
- Omit `{{DEITY_DESCRIPTION}}` if the source entry provides no narrative text.
- Alignment uses the display string format, not abbreviations (e.g., `Neutral Evil` not `NE`).
