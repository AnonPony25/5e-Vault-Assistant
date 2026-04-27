---
name: 3-mechanics-spell
description: Use when creating or editing a D&D 5e spell file in the 3-Mechanics repository (spells/ folder). Provides the correct Obsidian/5etools Markdown structure with json5e-spell cssclass, multi-class and subclass tags, spell level/school tags, casting time, range, components, duration, description, upgrade text, and class list links.
---

# 3-Mechanics Spell File Template

Use this skill when creating or editing files inside spells/ in the 3-Mechanics vault.

## File Naming

SPELL_SLUG-SOURCE_CODE.md
Examples: acid-splash-xphb.md, fireball-xphb.md, healing-word-phb.md

## Full Template

frontmatter fields:
- obsidianUIMode: preview
- cssclasses: json5e-spell
- tags (include all that apply):
  - ttrpg-cli/compendium/src/5e/SOURCE_CODE
  - ttrpg-cli/spell/class/CLASS_SLUG (one per class that has this spell)
  - ttrpg-cli/spell/level/LEVEL (cantrip, 1st, 2nd, ... 9th)
  - ttrpg-cli/spell/school/SCHOOL (evocation, conjuration, etc.)
  - ttrpg-cli/spell/subclass/SUBCLASS_SLUG (one per subclass that gains this spell)
  - ttrpg-cli/spell/optfeature/OPTFEATURE_SLUG (if available via pact/feature)
  - ttrpg-cli/spell/feat/FEAT_SLUG (if granted by a feat)
  - ttrpg-cli/spell/race/RACE_SLUG (if granted by a race)
- aliases: SPELL_NAME

Heading: # SPELL_NAME
Comment line (required): %%-- Embedded content starts on the next line. --%% 
Level/School line: *LEVEL, SCHOOL* (e.g. *cantrip, Evocation* or *3rd-level, Conjuration*)

Stats block (bullet list):
- **Casting time:** CASTING_TIME
- **Range:** RANGE
- **Components:** COMPONENTS (V, S, M (material description))
- **Duration:** DURATION

Spell description paragraph(s).

Upgrade section (if applicable):
**At Higher Levels** or **Cantrip Upgrade.** UPGRADE_TEXT

Classes line:
**Classes**: [Class Name](z_CLI/lists/list-spells-classes-CLASS_SLUG.md); [Subclass (Name)](z_CLI/lists/list-spells-classes-SUBCLASS_SLUG.md "subclass=SOURCE;class=SOURCE")

Source line: *Source: FULL_CITATION*

## Field Reference

- LEVEL: cantrip, 1st-level, 2nd-level, ... 9th-level
- SCHOOL: Abjuration, Conjuration, Divination, Enchantment, Evocation, Illusion, Necromancy, Transmutation
- COMPONENTS: V (Verbal), S (Somatic), M (Material with description in parentheses)
- DURATION: Instantaneous, Concentration up to N minutes/hours, N rounds, etc.

## Notes

- cssclasses must be json5e-spell
- The %%-- Embedded content --%%  comment is required immediately after frontmatter
- Dice expressions use backtick format: `2d6`, `1d8`
- Conditions link to z_CLI/rules/conditions.md#ConditionName
- Area of effect types link to z_CLI/rules/variant-rules/AREA_TYPE-xphb.md
- Spell upgrade text uses "**At Higher Levels.**" for leveled spells and "**Cantrip Upgrade.**" for cantrips
- The Classes line lists all classes/subclasses with proper internal links including subclass query parameters
