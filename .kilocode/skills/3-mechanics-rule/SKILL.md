---
name: 3-mechanics-rule
description: Use when creating or editing a D&D 5e core rule reference file in the 3-Mechanics repository (rules/ folder, excluding variant-rules/). These files cover conditions, actions, senses, skills, damage types, diseases, item properties, and similar core rules. Provides the correct Obsidian/5etools Markdown structure with json5e-note cssclass and per-entry source citations.
---

# 3-Mechanics Rule File Template

Use this skill when creating or editing files inside rules/ (NOT rules/variant-rules/).

## File Naming

conditions.md, actions.md, skills.md, senses.md, damage-types.md

## Template Structure

frontmatter fields:
- obsidianUIMode: preview
- cssclasses: json5e-note
- tags: ttrpg-cli/compendium/src/5e/SOURCE_CODE
- aliases: RULE_TITLE

Heading: # RULE_TITLE

For each rule entry:
  ## ENTRY_NAME
  _Source: FULL_SOURCE_CITATION_

  Intro paragraph describing the rule entry.

  **Effect Name.** Effect mechanical text with rule links.

  **Effect Name 2.** Effect mechanical text.

## Field Reference

- SOURCE_CODE: lowercase source abbreviation, e.g. xphb
- RULE_TITLE: overall file title, e.g. Conditions, Actions
- ENTRY_NAME: individual entry name, e.g. Blinded, Charmed, Attack
- FULL_SOURCE_CITATION: e.g. Player's Handbook (2024) p. 361. Available in the SRD and the Free Rules (2024)

## Notes

- cssclasses must be json5e-note
- Each entry in the file gets its own ## heading and _Source_ citation
- SRD-eligible entries note availability: Available in the SRD (5.2) and the Free Rules (2024)
- Cross-reference links use z_CLI/rules/variant-rules/SLUG.md format
- Ability/skill checks link to z_CLI/rules/skills.md#SkillName
