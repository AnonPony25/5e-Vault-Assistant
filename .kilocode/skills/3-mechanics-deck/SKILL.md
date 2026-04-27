---
name: 3-mechanics-deck
description: Use when creating or editing a D&D 5e card deck file in the 3-Mechanics repository (decks/ folder). Provides the correct Obsidian/5etools Markdown structure with json5e-deck cssclass, deck description, and a rollable dice table of cards.
---

# 3-Mechanics Deck File Template

Use this skill whenever you need to create or modify a file inside `decks/` in the 3-Mechanics vault.

## File Naming Convention

```
<deck-slug>-<source-code>.md
```
Examples: `deck-of-illusions-xdmg.md`, `deck-of-many-things-xdmg.md`

## Full Template

```markdown
---
obsidianUIMode: preview
cssclasses:
- json5e-deck
tags:
- ttrpg-cli/compendium/src/5e/{{SOURCE_CODE}}
aliases:
- "{{NAME}}"
---
# {{NAME}}
*Source: {{SOURCE_FULL}}*  

{{DECK_DESCRIPTION}}

**{{NAME}}**

| dice: 1d{{DICE_SIZE}} | Card | Effect |
|---|---|---|
| {{ROLL_RANGE_1}} | {{CARD_NAME_1}} | [{{LINK_TEXT_1}}](z_CLI/{{LINK_PATH_1}}.md) |
| {{ROLL_RANGE_2}} | {{CARD_NAME_2}} | [{{LINK_TEXT_2}}](z_CLI/{{LINK_PATH_2}}.md) |
| {{ROLL_RANGE_3}} | {{CARD_NAME_3}} | {{PLAIN_TEXT_3}} |
^{{TABLE_ID}}
```

## Field Reference

| Placeholder | Description |
|---|---|
| `{{SOURCE_CODE}}` | Lowercase source abbreviation, e.g. `xdmg`, `dmg` |
| `{{NAME}}` | Full display name of the deck |
| `{{SOURCE_FULL}}` | Full book title + page |
| `{{DECK_DESCRIPTION}}` | Narrative description: how many cards, how to draw, effects |
| `{{DICE_SIZE}}` | Number of sides matching the total card count range, e.g. `100` for d% |
| `{{ROLL_RANGE_N}}` | Roll range like `01-03` or single value `1` |
| `{{CARD_NAME_N}}` | Name of the card in this slot |
| `{{TABLE_ID}}` | Block ID for the table, typically kebab-case deck name |

## Notes

- `cssclasses` must be `json5e-deck`.
- The deck table uses a `dice:` column header so Obsidian can roll on it.
- Cards that link to bestiary entries use `z_CLI/bestiary/{{type}}/{{slug}}.md`.
- For condition cards or spell cards, link to `z_CLI/rules/conditions.md` or `z_CLI/spells/{{slug}}.md`.
- The `^{{TABLE_ID}}` block ID goes on the line immediately after the table.
