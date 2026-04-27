---
name: 1-party-character
description: Use when creating or editing a player character file in 1-Party/. Covers Meta Bind stat blocks, badges/healthpoints/ability/skills/consumable plugin blocks, spell slots, faction standings, and inventory dataview.
---

# 1-Party Character Skill

## File Location
`1-Party/<Party Name>/<Character Name>.md`

## Required Frontmatter
```yaml
aliases: [CharacterName]
tags:
  - Category/Player
Player: PlayerRealName
Role: Player
level: 1
hp: 10
max_hp: 10
ac: 10
modifier: 0
pasperc: 10
Status: Active
PlayerKnownLanguages: []
faction_standing: {}
char_race: Human
char_class: Fighter
char_gender: Male
char_status: Alive
char_age: Young Adult
char_items: []
Connected_Quests: []
Connected_Groups: []
parents: []
partner: []
children: []
enemies: []
allies: []
siblings: []
obsidianUIMode: preview
MyContainer:
```

## Plugin Blocks
| Block | Plugin | Purpose |
|---|---|---|
| `badges` | Badges | Level/Initiative/Spell Save/AC banners |
| `healthpoints` | Healthpoints | HP bar + hit dice |
| `ability` | Ability | 6 stat scores + modifiers |
| `skills` | Skills | Proficiency toggles |
| `consumable` | Consumable | Class features, spell slots, charges |

## Notes
- `Status: Active` drives party tracker queries.
- `faction_standing: {}` is a YAML map of "Faction": "Standing".
- Mermaid relationship diagram uses :::internal-link class; node labels must match note basenames.
