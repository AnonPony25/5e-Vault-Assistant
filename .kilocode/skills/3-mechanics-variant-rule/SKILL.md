---
name: 3-mechanics-variant-rule
description: Use when creating or editing a D&D 5e variant rule or optional rule reference file in the 3-Mechanics repository (rules/variant-rules/ subfolder). These are individual short-form rule glossary entries such as Ability Check, Advantage, Long Rest, Proficiency. Provides the correct Obsidian/5etools Markdown structure with json5e-note cssclass and single-entry format.
---

# 3-Mechanics Variant Rule File Template

Use this skill when creating or editing files inside rules/variant-rules/ in the 3-Mechanics vault.

## File Naming

ability-check-xphb.md, advantage-xphb.md, long-rest-xphb.md, proficiency-xphb.md

## Template Structure

frontmatter fields:
- obsidianUIMode: preview
- cssclasses: json5e-note
- tags: ttrpg-cli/compendium/src/5e/SOURCE_CODE
- aliases: RULE_NAME

Heading: # RULE_NAME
Source line: *Source: FULL_SOURCE_CITATION*

Single paragraph or short multi-paragraph description of the rule.
Include all mechanics, cross-references as links, and sub-effects as bold labels.

## Field Reference

- SOURCE_CODE: lowercase source abbreviation, e.g. xphb, phb, dmg
- RULE_NAME: display name, e.g. Ability Check, Advantage, Proficiency Bonus
- FULL_SOURCE_CITATION: e.g. Player's Handbook (2024) p. 360. Available in the SRD and the Free Rules (2024)

## Notes

- cssclasses must be json5e-note
- Unlike the main rules/ files, variant-rule files typically cover a single concept per file
- Source line appears immediately after the heading using italic format: *Source: ...*
- SRD-eligible rules include the availability note in the source line
- Cross-references link to other variant-rules files: [D20 Test](z_CLI/rules/variant-rules/d20-test-xphb.md)
- These files are short (one to a few paragraphs) — do not add multiple ## sections unless the rule has named sub-rules
