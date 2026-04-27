---
name: 3-mechanics-table
description: Use when creating or editing a D&D 5e random table file in the 3-Mechanics repository (tables/ folder). These are standalone rollable tables (name tables, loot tables, encounter tables, etc.). Provides the correct Obsidian/5etools Markdown structure with json5e-note cssclass, dice column header, and block ID.
---

# 3-Mechanics Table File Template

Use this skill when creating or editing files inside tables/ in the 3-Mechanics vault.

## File Naming

TABLE_TITLE_SLUG-SOURCE_CODE.md
Examples: 1-common-names-xdmg.md, 100-gp-gemstones-xdmg.md, trinkets-phb.md

Numeric prefixes represent the table number within the source if applicable.

## Full Template

frontmatter fields:
- obsidianUIMode: preview
- cssclasses: json5e-note
- tags: ttrpg-cli/compendium/src/5e/SOURCE_CODE
- aliases: TABLE_TITLE

Heading: # TABLE_TITLE
Source line: *Source: FULL_CITATION*

Table with dice roller header and block ID:

**TABLE_TITLE**

| dice: NdN | COLUMN_1 | COLUMN_2 |
|---|---|---|
| ROLL_RANGE | VALUE_1A | VALUE_1B |
| ROLL_RANGE | VALUE_2A | VALUE_2B |
^TABLE_ID

## Field Reference

- SOURCE_CODE: lowercase source abbreviation
- TABLE_TITLE: display title matching the source, e.g. 1: Common Names
- FULL_CITATION: Book title + page, e.g. Dungeon Master's Guide (2024) p. 84
- NdN: dice notation matching the table range, e.g. 1d12, 1d100, 1d20
- TABLE_ID: kebab-case block ID, e.g. 1-common-names or trinkets

## Notes

- cssclasses must be json5e-note (tables are notes)
- The first column header uses "dice: NdN" format so Obsidian can roll on the table
- The block ID (^TABLE_ID) goes on the line immediately after the last table row
- For d% tables use 1d100 with roll ranges formatted as 01-05, 06-10, etc.
- Tables with linked entries use [Entry Name](z_CLI/PATH.md) format in cells
- Some tables have only one data column; omit extra columns if not needed
- The bold table title above the table matches the alias exactly
