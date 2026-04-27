---
name: 3-mechanics-reward
description: Use when creating or editing a D&D 5e supernatural reward, boon, or curse file in the 3-Mechanics repository (rewards/ folder). Provides the correct Obsidian/5etools Markdown structure with json5e-reward cssclass, reward type tag, and sections for Pronouncement, Burden, and Resolution.
---

# 3-Mechanics Reward File Template

Use this skill whenever you need to create or modify a file inside rewards/ in the 3-Mechanics vault.

## File Naming Convention

ancient-seal-vrgr.md, arcane-study-charm-xdmg.md, charm-of-restoration-xdmg.md

## Reward Type Tags

| Reward Category | Tag Suffix |
|---|---|
| Boon | boon |
| Charm | charm |
| Curse | curse |
| Epic Boon | epic-boon |
| Other | other |

## Template Fields

frontmatter:
- obsidianUIMode: preview
- cssclasses: json5e-reward
- tags: ttrpg-cli/compendium/src/5e/SOURCE_CODE and ttrpg-cli/reward/REWARD_TYPE
- aliases: NAME

Heading: # NAME
Subheading: *REWARD_CATEGORY* (e.g. Curse, Charm, Boon)

For Curses include sections:
- narrative intro paragraph
- ## Pronouncement (in-world text)
- ## Burden (mechanical effect)
- ## Resolution (how to lift the curse)
- italic source line at end

For Charms/Boons include:
- single description paragraph with mechanical benefit
- italic source line at end

## Notes

- cssclasses must be json5e-reward
- Links to monsters use z_CLI/bestiary/TYPE/SLUG.md format
- Source line format: *Source: Book Title p. N*
