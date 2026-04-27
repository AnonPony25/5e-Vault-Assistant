---
name: 3-mechanics-item
description: Use when creating or editing a D&D 5e magic item or equipment file in the 3-Mechanics repository (items/ folder). Provides the correct Obsidian/5etools Markdown structure with json5e-item cssclass, rarity, attunement, gear type tags, and item description.
---

# 3-Mechanics Item File Template

Use this skill whenever you need to create or modify a file inside `items/` in the 3-Mechanics vault.

## File Naming Convention

```
<bonus-prefix-><item-slug>-<source-code>.md
```
Examples: `1-all-purpose-tool-tce.md`, `bag-of-holding-xdmg.md`, `longsword-xphb.md`

Use numeric prefix for bonus items: `1-`, `2-`, `3-` (for +1, +2, +3).

## Full Template

```markdown
---
obsidianUIMode: preview
cssclasses:
- json5e-item
tags:
- ttrpg-cli/compendium/src/5e/{{SOURCE_CODE}}
- ttrpg-cli/item/attunement/{{ATTUNEMENT_TAG}}
- ttrpg-cli/item/gear/{{GEAR_TYPE_TAG}}
- ttrpg-cli/item/rarity/{{RARITY_TAG}}
aliases:
- "{{NAME}}"
---
# {{NAME}}
*{{ITEM_TYPE}}, {{RARITY}}{{ATTUNEMENT_CLAUSE}}*  

{{ITEM_DESCRIPTION}}

*Source: {{SOURCE_FULL}}*
```

## Field Reference

| Placeholder | Description |
|---|---|
| `{{SOURCE_CODE}}` | Lowercase source abbreviation |
| `{{ATTUNEMENT_TAG}}` | `required` if attunement is required, `optional` if optional; omit tag line entirely if no attunement |
| `{{GEAR_TYPE_TAG}}` | Category slug, e.g. `spellcasting-focus`, `weapon`, `armor`, `wondrous` |
| `{{RARITY_TAG}}` | Lowercase rarity: `common`, `uncommon`, `rare`, `very-rare`, `legendary`, `artifact` |
| `{{NAME}}` | Full display name including any bonus prefix |
| `{{ITEM_TYPE}}` | Type string, e.g. `Wondrous item`, `Weapon (longsword)`, `Armor (chain mail)` |
| `{{RARITY}}` | Display rarity, e.g. `uncommon`, `rare` |
| `{{ATTUNEMENT_CLAUSE}}` | ` (requires attunement)` or ` (requires attunement by a {{CLASS}})` or empty |
| `{{ITEM_DESCRIPTION}}` | Full item description with mechanical text and embedded links |
| `{{SOURCE_FULL}}` | Full book title + page |

## Notes

- `cssclasses` must be `json5e-item`.
- The item type line (after the `# Name` heading) uses italics with a trailing double-space for a line break.
- All condition, spell, and rule references use `z_CLI/` path links.
- For weapons with attack/damage stats, add them inline in the description paragraph.
- Omit `ttrpg-cli/item/attunement/` tag entirely if the item requires no attunement.
