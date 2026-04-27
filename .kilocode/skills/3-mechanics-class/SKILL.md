---
name: 3-mechanics-class
description: Use when creating or editing a D&D 5e class or subclass file in the 3-Mechanics repository (classes/ folder). Provides the correct Obsidian/5etools Markdown structure with class-progression table, subclass features, and spell tables.
---

# 3-Mechanics Class/Subclass File Template

Use this skill whenever you need to create or modify a file inside `classes/` in the 3-Mechanics vault.

## File Naming Convention

```
<parent-class-slug>-<subclass-slug>-<source-code>.md
```
Examples: `artificer-alchemist-tce.md`, `wizard-evoker-xphb.md`

For base classes: `<class-slug>-<source-code>.md`, e.g. `fighter-xphb.md`

## Full Template

```markdown
---
obsidianUIMode: preview
cssclasses:
- json5e-class
tags:
- ttrpg-cli/compendium/src/5e/{{SOURCE_CODE}}
- ttrpg-cli/subclass/{{PARENT_CLASS}}/{{SUBCLASS_SLUG}}
aliases:
- "{{SUBCLASS_NAME}}"
---
# {{SUBCLASS_NAME}}
*[{{PARENT_CLASS_NAME}}](./{{PARENT_CLASS_SLUG}}.md): {{ARCHETYPE_CATEGORY}}*  
*Source: {{SOURCE_FULL}}*  

> [!tldr] Class and Feature Progression
> 
> <table class="class-progression">
> <thead>
> <tr><th colspan='3'></th></tr>
> <tr class="class-progression"><th class"level">Level</th><th class"pb">PB</th><th class"feature">Features</th></tr>
> </thead><tbody>
> <tr class="class-progression"><td class"level">1st</td><td class"pb">+2</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">2nd</td><td class"pb">+2</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">3rd</td><td class"pb">+2</td><td class"feature"><a href='#{{SUBCLASS_NAME}} (Level 3)' class='internal-link'>{{SUBCLASS_NAME}}</a></td></tr>
> <tr class="class-progression"><td class"level">4th</td><td class"pb">+2</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">5th</td><td class"pb">+3</td><td class"feature"><a href='#{{FEATURE_2}} (Level 5)' class='internal-link'>{{FEATURE_2}}</a></td></tr>
> <tr class="class-progression"><td class"level">6th</td><td class"pb">+3</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">7th</td><td class"pb">+3</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">8th</td><td class"pb">+3</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">9th</td><td class"pb">+4</td><td class"feature"><a href='#{{FEATURE_3}} (Level 9)' class='internal-link'>{{FEATURE_3}}</a></td></tr>
> <tr class="class-progression"><td class"level">10th</td><td class"pb">+4</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">11th</td><td class"pb">+4</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">12th</td><td class"pb">+4</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">13th</td><td class"pb">+5</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">14th</td><td class"pb">+5</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">15th</td><td class"pb">+5</td><td class"feature"><a href='#{{FEATURE_4}} (Level 15)' class='internal-link'>{{FEATURE_4}}</a></td></tr>
> <tr class="class-progression"><td class"level">16th</td><td class"pb">+5</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">17th</td><td class"pb">+6</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">18th</td><td class"pb">+6</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">19th</td><td class"pb">+6</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">20th</td><td class"pb">+6</td><td class"feature"></td></tr>
> </tbody></table>

^class-progression

{{SUBCLASS_DESCRIPTION}}

## Subclass Features

### {{FEATURE_1_NAME}} (Level {{FEATURE_1_LEVEL}})

{{FEATURE_1_DESCRIPTION}}

### Subclass Spells (Level {{FEATURE_1_LEVEL}})

**{{SUBCLASS_NAME}} Spells**

| {{PARENT_CLASS_TITLE}} Level | Spell |
|---|---|
| {{SPELL_LEVEL_1}} | [{{SPELL_1}}](z_CLI/spells/{{SPELL_1_SLUG}}.md), [{{SPELL_2}}](z_CLI/spells/{{SPELL_2_SLUG}}.md) |
| {{SPELL_LEVEL_2}} | [{{SPELL_3}}](z_CLI/spells/{{SPELL_3_SLUG}}.md), [{{SPELL_4}}](z_CLI/spells/{{SPELL_4_SLUG}}.md) |
^{{SUBCLASS_SLUG}}-spells

### {{FEATURE_2_NAME}} (Level {{FEATURE_2_LEVEL}})

{{FEATURE_2_DESCRIPTION}}

### {{FEATURE_3_NAME}} (Level {{FEATURE_3_LEVEL}})

{{FEATURE_3_DESCRIPTION}}

### {{FEATURE_4_NAME}} (Level {{FEATURE_4_LEVEL}})

{{FEATURE_4_DESCRIPTION}}
```

## Field Reference

| Placeholder | Description |
|---|---|
| `{{SOURCE_CODE}}` | Lowercase source abbreviation |
| `{{PARENT_CLASS}}` | Lowercase parent class slug, e.g. `artificer`, `wizard` |
| `{{SUBCLASS_SLUG}}` | Lowercase subclass slug, e.g. `alchemist`, `evoker` |
| `{{SUBCLASS_NAME}}` | Display name of the subclass |
| `{{PARENT_CLASS_NAME}}` | Display name of the parent class |
| `{{ARCHETYPE_CATEGORY}}` | Archetype category text, e.g. `Artificer Specialist` |
| `{{FEATURE_N}}` | Feature name for class-progression links |
| `{{SUBCLASS_SLUG}}-spells` | Block ID for the spells table |
| `{{SOURCE_FULL}}` | Full book title and page |

## Notes

- The `^class-progression` block ID must follow the closing `</tbody></table>` line.
- Proficiency bonus increases at levels 5 (+3), 9 (+4), 13 (+5), 17 (+6).
- Link to the parent class file using a relative path `./{{PARENT_CLASS_SLUG}}.md`.
- Omit the Subclass Spells table if the subclass does not grant bonus spells.
- Each named feature's level heading uses the format `### Feature Name (Level N)`.
