---
name: 3-mechanics-vehicle
description: Use when creating or editing a D&D 5e vehicle file in the 3-Mechanics repository (vehicles/ folder). Provides the correct Obsidian/5etools Markdown structure with json5e-vehicle cssclass, terrain and size tags, ad-statblock callout with crew capacity, AC, HP, speed, and optional control/lever tables.
---

# 3-Mechanics Vehicle File Template

Use this skill when creating or editing files inside vehicles/ in the 3-Mechanics vault.

## File Naming

VEHICLE_SLUG-SOURCE_CODE.md
Examples: apparatus-of-kwalish-xdmg.md, battle-balloon-ai.md, astral-brig-mtf.md

## Vehicle Terrain Tags

| Terrain | Tag |
|---|---|
| Land | ttrpg-cli/vehicle/terrain/land |
| Sea | ttrpg-cli/vehicle/terrain/sea |
| Air | ttrpg-cli/vehicle/terrain/air |
| Space | ttrpg-cli/vehicle/terrain/space |

## Vehicle Type Tags

| Type | Tag |
|---|---|
| Object (self-propelled) | ttrpg-cli/vehicle/type/object |
| Ship (crewed vessel) | ttrpg-cli/vehicle/type/ship |
| Spelljammer | ttrpg-cli/vehicle/type/spelljammer |

## Full Template

frontmatter fields:
- obsidianUIMode: preview
- cssclasses: json5e-vehicle
- tags:
  - ttrpg-cli/compendium/src/5e/SOURCE_CODE
  - ttrpg-cli/vehicle/size/SIZE
  - ttrpg-cli/vehicle/terrain/TERRAIN
  - ttrpg-cli/vehicle/type/VEHICLE_TYPE
- aliases: NAME

Heading: # NAME
Comment (required): %%-- Embedded content starts on the next line. --%%
Source line: *Source: FULL_CITATION*

ad-statblock callout:

```ad-statblock
title: NAME
![](TOKEN_URL#token)
*SIZE_TITLE vehicle; TERRAIN*

- **Creature Capacity** N crew, N passenger(s)
- **Armor Class** AC
- **Hit Points** HP
- **Speed** SPEED

Ability score table (6 columns STR through CHA, typically all 10 +0)

- **Damage Immunities** poison, psychic (and others)

Vehicle description paragraph.

Optional control table:
**Control Table Name**
| Control | Up | Down |
|---|---|---|
| 1 | Effect | Effect |
```
^statblock

## Field Reference

- SOURCE_CODE: lowercase source abbreviation
- SIZE: lowercase vehicle size, e.g. large, huge, gargantuan
- TERRAIN: lowercase terrain type from table above
- VEHICLE_TYPE: type slug from table above
- TOKEN_URL: full URL to token image on 5etools CDN or 3-Mechanics assets
- SIZE_TITLE: title-case size
- CREW: number of crew members required to operate
- HP: hit point total

## Notes

- cssclasses must be json5e-vehicle
- The %%-- Embedded content --%% comment is required right after frontmatter
- The ^statblock block ID goes on the line after the closing backticks
- All ability scores are typically 10 (+0) for vehicles unless specified otherwise
- Include Damage Immunities for poison and psychic at minimum
- Speed includes all movement modes: 30 ft., swim 30 ft., fly 60 ft., etc.
