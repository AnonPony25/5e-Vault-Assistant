---
name: 3-mechanics-trap-hazard
description: Use when creating or editing a D&D 5e trap or hazard file in the 3-Mechanics repository (traps-hazards/ folder). Provides the correct Obsidian/5etools Markdown structure with json5e-hazard cssclass, hazard type tag, and sections for Trigger, Effect, and Countermeasures.
---

# 3-Mechanics Trap/Hazard File Template

Use this skill when creating or editing files inside traps-hazards/ in the 3-Mechanics vault.

## File Naming

TRAP_SLUG-SOURCE_CODE.md
Examples: bear-trap-xge.md, avalanche-tce.md, arcane-effluence-nf.md

## Hazard Type Tags

| Category | Tag Suffix |
|---|---|
| Simple trap | smpl |
| Complex trap | cmpx |
| Environmental hazard | env |
| Generic/Other | gnrc |

## Full Template

frontmatter fields:
- obsidianUIMode: preview
- cssclasses: json5e-hazard
- tags: ttrpg-cli/compendium/src/5e/SOURCE_CODE and ttrpg-cli/hazard/HAZARD_TYPE
- aliases: NAME

Heading: # NAME
Subheading line: *HAZARD_CATEGORY* (e.g. Generic Hazard, Simple Trap, Complex Trap, Environmental Hazard)

Description paragraph explaining the trap/hazard.

Optional sections (include if source provides them):
## Trigger
Description of what activates the trap.

## Effect
Mechanical effect when triggered (attack roll, saving throw DC, damage).

## Countermeasures
How to detect and disarm the trap (Perception/Investigation DC, thieves' tools DC).

Source line: *Source: FULL_CITATION*

## Field Reference

- SOURCE_CODE: lowercase source abbreviation
- HAZARD_TYPE: tag suffix from table above
- NAME: display name of the trap or hazard
- HAZARD_CATEGORY: display string, e.g. Generic Hazard, Simple Trap

## Notes

- cssclasses must be json5e-hazard
- Many simple traps in the repository have only a description paragraph and no sub-sections
- Complex traps include Initiative order, active elements, and multiple effect entries
- Saving throw DCs and damage dice use standard formatting: DC 14 Strength saving throw, 2d6 piercing damage
- Conditions imposed link to z_CLI/rules/conditions.md#ConditionName
