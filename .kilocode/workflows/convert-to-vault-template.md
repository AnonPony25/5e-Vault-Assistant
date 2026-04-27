---
name: convert-to-vault-template
description: >
  Converts an external or unformatted note (plain markdown, JSON, CSV, 5etools
  export, DNDBeyond copy-paste, or raw text) into the correct 5e-Vault-Assistant
  Obsidian template. Determines the target folder, loads the matching skill,
  maps fields to frontmatter, and outputs a fully-formed note.
---

# Workflow: Convert to Vault Template

## Step 1 -- Identify Note Type

| If source contains | Destination | Skill |
|---|---|---|
| AC, HP, CR, attack rolls | 3-Mechanics/bestiary/<type>/ | 3-mechanics-bestiary |
| Spell level, casting time, components | 3-Mechanics/spells/ | 3-mechanics-spell |
| Magic item, attunement, rarity | 3-Mechanics/items/ | 3-mechanics-item |
| Class table, hit die, proficiencies | 3-Mechanics/classes/ | 3-mechanics-class |
| Skill profs, feature name, personality tables | 3-Mechanics/backgrounds/ | 3-mechanics-background |
| Feat category, prerequisite | 3-Mechanics/feats/ | 3-mechanics-feat |
| Domains, alignment, pantheon | 3-Mechanics/deities/ | 3-mechanics-deity |
| Bastion facilities, defense bonus, owner | 3-Mechanics/bastions/ | 3-mechanics-bastion |
| Card names, draw rules | 3-Mechanics/decks/ | 3-mechanics-deck |
| Object AC/HP, damage immunities | 3-Mechanics/objects/ | 3-mechanics-object |
| Optional feature type, pact/invocation | 3-Mechanics/optional-features/ | 3-mechanics-optional-feature |
| Race traits, speed, creature type | 3-Mechanics/races/ | 3-mechanics-race |
| Reward type | 3-Mechanics/rewards/ | 3-mechanics-reward |
| Rule description, examples | 3-Mechanics/rules/ | 3-mechanics-rule |
| Variant rule, optional rule | 3-Mechanics/rules/variant-rules/ | 3-mechanics-variant-rule |
| Rollable table, dice expression | 3-Mechanics/tables/ | 3-mechanics-table |
| Trap trigger, save DC, disarm DC | 3-Mechanics/traps-hazards/ | 3-mechanics-trap-hazard |
| Vehicle speed, helm action, hull HP | 3-Mechanics/vehicles/ | 3-mechanics-vehicle |
| char_race, char_status, NPC | 2-World/People/ | 2-world-person |
| questStatus, questGiver | 2-World/Quests/ | 2-world-quest |
| hubType, district, population | 2-World/Hubs/ | 2-world-hub |
| leader, officers, faction benefits | 2-World/Groups/ | 2-world-group |
| Region, climate, dominant races | 2-World/Regions/ | 2-world-region |
| POI type, dungeon, ruin | 2-World/Points of Interest/ | 2-world-poi |
| Place category (Commerce/Military) | 2-World/Places/ | 2-world-place |
| sessionDate, roster, OneLiner | 1-Session Journals/ | 1-session-journal |
| Player stats, spell slots, abilities | 1-Party/<Party>/ | 1-party-character |
| Draft / unformatted | 0-Scratch Notes/ | 0-scratch-notes |

## Step 2 -- Load Skill
Load the skill from Step 1 and follow its field reference tables.

## Step 3 -- Map Fields

### Generic Rules
- Name/Title -> aliases array + file name
- Source book -> detect abbreviation (Player's Handbook 2024 -> xphb; Monster Manual -> mm; unknown -> homebrew)
- Description -> main description section
- Numeric stats -> correct frontmatter keys per skill
- Lists -> YAML arrays
- Tables -> Markdown tables
- Linked entities -> [[WikiLink]] using basenames

### Field Quick-Reference

| Source | Frontmatter key |
|---|---|
| Creature type | tags: ttrpg-cli/monster/type/TYPE |
| Challenge rating | cr: "N" |
| Spell school | tags: ttrpg-cli/spell/school/SCHOOL |
| Spell level | tags: ttrpg-cli/spell/level/LEVEL |
| Item rarity | tags: ttrpg-cli/item/rarity/RARITY |
| NPC race | char_race: |
| NPC alive/dead | char_status: |
| Quest status | questStatus: |
| Hub settlement type | hubType: |

## Step 4 -- Construct Output
1. Write full YAML frontmatter
2. Write Templater <%* ... -%> script with tp.file.rename + processFrontMatter
3. Write Meta Bind callout layout with tabs
4. Write all body sections per skill spec
5. Write all Dataview/DataviewJS queries

## Step 5 -- Validate
- [ ] tags array contains Category/<Type>
- [ ] obsidianUIMode: preview set (scratch notes use source)
- [ ] cssclasses has correct json5e-* for Mechanics notes
- [ ] Wikilinks use [[Path|Alias]] format
- [ ] ^statblock present after every ad-statblock block
- [ ] File name follows skill naming convention

## Step 6 -- Deliver
Output the note as a fenced Markdown block.
For batch conversions, number each output.

### Edge Cases
- 5etools JSON: parse name, source, cr, type, ac[0].ac, hp.average, hp.formula, ability scores, trait/action/reaction arrays
- DNDBeyond copy-paste: extract name/stats from stat block header; features from bulleted sections
- Incomplete vault note: preserve all existing fields; only add missing ones
- Unknown source: default to homebrew
