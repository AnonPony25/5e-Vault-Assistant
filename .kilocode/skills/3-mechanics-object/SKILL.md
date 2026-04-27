---
name: 3-mechanics-object
description: Use when creating or editing a D&D 5e object or siege weapon file in the 3-Mechanics repository (objects/ folder). Provides the correct Obsidian/5etools Markdown structure with json5e-object cssclass, size/type tags, and an ad-statblock callout with AC, HP, and actions.
---

# 3-Mechanics Object File Template

Use this skill whenever you need to create or modify a file inside `objects/` in the 3-Mechanics vault.

## File Naming Convention

```
<object-slug>-<source-code>.md
```
Examples: `ballista-xdmg.md`, `cannon.md`, `portcullis-xdmg.md`

## Full Template

```markdown
---
obsidianUIMode: preview
cssclasses:
- json5e-object
tags:
- ttrpg-cli/compendium/src/5e/{{SOURCE_CODE}}
- ttrpg-cli/object/size/{{SIZE}}
- ttrpg-cli/object/type/{{OBJECT_TYPE}}
aliases:
- "{{NAME}}"
---
# {{NAME}}
%%-- Embedded content starts on the next line. --%%
*Source: {{SOURCE_FULL}}*  

{{OBJECT_DESCRIPTION}}

```ad-statblock
title: {{NAME}}
![]({{TOKEN_URL}}#token)
*{{SIZE_TITLE}} {{OBJECT_TYPE_DISPLAY}}*

- **Armor Class** {{AC}}
- **Hit Points** {{HP}}
- **Speed** {{SPEED}}

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|{{STR}} ({{STR_MOD}})|{{DEX}} ({{DEX_MOD}})|{{CON}} ({{CON_MOD}})|{{INT}} ({{INT_MOD}})|{{WIS}} ({{WIS_MOD}})|{{CHA}} ({{CHA_MOD}})|

{{SPECIAL_TRAITS}}

## Actions

***{{ACTION_NAME}} ({{ACTION_REQUIREMENTS}}).*** *{{ATTACK_TYPE}}:* `+{{ATTACK_BONUS}}`, range {{RANGE}} ft. *Hit:* {{DAMAGE}} {{DAMAGE_TYPE}} damage.
```
^statblock
```

## Field Reference

| Placeholder | Description |
|---|---|
| `{{SOURCE_CODE}}` | Lowercase source abbreviation |
| `{{SIZE}}` | Lowercase size: `tiny`, `small`, `medium`, `large`, `huge`, `gargantuan` |
| `{{OBJECT_TYPE}}` | Lowercase type slug, e.g. `siege-weapon`, `trap`, `structure` |
| `{{NAME}}` | Display name |
| `{{SOURCE_FULL}}` | Full book title + page |
| `{{TOKEN_URL}}` | Full URL to the token image on the 5etools CDN |
| `{{SIZE_TITLE}}` | Title-cased size |
| `{{OBJECT_TYPE_DISPLAY}}` | Display string for the type, e.g. `Siege weapon` |
| `{{ACTION_REQUIREMENTS}}` | Requirements to use the action, e.g. `Requires Load and Aim` |
| `{{ATTACK_TYPE}}` | `Ranged Attack Roll` or `Melee Attack Roll` |

## Notes

- `%%-- Embedded content starts on the next line. --%%` comment is required right after the YAML frontmatter block.
- `cssclasses` must be `json5e-object`.
- The `^statblock` block ID must follow the closing backticks of the ad-statblock callout.
- Objects typically have all ability scores at 10 (+0) unless the source specifies otherwise.
- Omit the Speed line entirely if the object cannot move.
- `{{SPECIAL_TRAITS}}` is a line like `- **Damage Immunities** poison, psychic` — list only applicable immunities/resistances.
