---
name: 3-mechanics-bestiary
description: Use when creating or editing a D&D 5e monster/creature file in the 3-Mechanics repository (bestiary/ and its subfolders: beast, elemental, humanoid, undead, etc.). Provides correct Obsidian/5etools Markdown structure with statblock frontmatter fields, ad-statblock callout, stat array, traits, actions, bonus actions, and reactions.
---

# 3-Mechanics Bestiary File Template

Use this skill whenever you need to create or modify a file inside `bestiary/` or any of its type subdirectories in the 3-Mechanics vault.

## File Naming Convention

```
<creature-slug>-<source-code>.md
```
Place the file inside the appropriate subdirectory matching the monster type:
`bestiary/beast/`, `bestiary/humanoid/`, `bestiary/elemental/`, `bestiary/undead/`, etc.

## Full Template

```markdown
---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/{{SOURCE_CODE}}
- ttrpg-cli/monster/cr/{{CR}}
- ttrpg-cli/monster/size/{{SIZE}}
- ttrpg-cli/monster/type/{{TYPE}}
statblock: true
statblock-link: "#^statblock"
name: {{NAME}}
ac: {{AC}}
hp: {{HP}}
modifier: {{INITIATIVE_MODIFIER}}
hit_dice: {{HIT_DICE}}
cr: '{{CR}}'
stats:
- {{STR}}
- {{DEX}}
- {{CON}}
- {{INT}}
- {{WIS}}
- {{CHA}}
source:
- {{SOURCE_CODE_UPPER}}
aliases:
- "{{NAME_ALIAS}}"
---
# {{NAME}}

![{{NAME}}](3-Mechanics/CLI/bestiary/{{TYPE}}/img/{{SLUG}}.webp#right)

{{LORE_DESCRIPTION}}

## Statblock

```ad-statblock
title: {{NAME}}
![](3-Mechanics/CLI/bestiary/{{TYPE}}/token/{{SLUG}}.webp#token)
*{{SIZE_TITLE}} {{TYPE_TITLE}}, {{ALIGNMENT}}*

- **Armor Class** {{AC}} ({{AC_SOURCE}})
- **Hit Points** {{HP}} ({{HIT_DICE}})
- **Speed** {{SPEED}}

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|{{STR}} ({{STR_MOD}})|{{DEX}} ({{DEX_MOD}})|{{CON}} ({{CON_MOD}})|{{INT}} ({{INT_MOD}})|{{WIS}} ({{WIS_MOD}})|{{CHA}} ({{CHA_MOD}})|

- **Proficiency Bonus** +{{PB}}
- **Saving Throws** {{SAVING_THROWS}}
- **Skills** {{SKILLS}}
- **Damage Immunities** {{DAMAGE_IMMUNITIES}}
- **Damage Resistances** {{DAMAGE_RESISTANCES}}
- **Condition Immunities** {{CONDITION_IMMUNITIES}}
- **Senses** {{SENSES}}, passive Perception {{PASSIVE_PERCEPTION}}
- **Languages** {{LANGUAGES}}
- **Challenge** {{CR}}

## Traits

***{{TRAIT_NAME}}.*** {{TRAIT_DESCRIPTION}}

## Actions

***{{ACTION_NAME}}.*** *Melee Weapon Attack:* +{{ATTACK_BONUS}} to hit, reach {{REACH}}, one target. *Hit:* {{DAMAGE}} {{DAMAGE_TYPE}} damage.

## Bonus Actions

***{{BONUS_ACTION_NAME}}.*** {{BONUS_ACTION_DESCRIPTION}}

## Reactions

***{{REACTION_NAME}}.*** {{REACTION_DESCRIPTION}}
```
^statblock

## Sources

*{{SOURCE_FULL}}*
```

## Field Reference

| Placeholder | Description |
|---|---|
| `{{SOURCE_CODE}}` | Lowercase source abbreviation, e.g. `xmm`, `mm`, `vgm` |
| `{{CR}}` | Challenge rating, e.g. `1/4`, `3`, `17` |
| `{{SIZE}}` | Lowercase size: `tiny`, `small`, `medium`, `large`, `huge`, `gargantuan` |
| `{{TYPE}}` | Lowercase monster type: `beast`, `humanoid`, `elemental`, etc. |
| `{{AC}}` | Armor Class number |
| `{{HP}}` | Average hit points number |
| `{{INITIATIVE_MODIFIER}}` | DEX modifier as integer |
| `{{HIT_DICE}}` | Dice expression, e.g. `8d12 + 16` |
| `{{STR}}` through `{{CHA}}` | Raw ability score numbers |
| `{{SOURCE_CODE_UPPER}}` | Uppercase source abbreviation, e.g. `XMM`, `MM` |
| `{{SLUG}}` | Kebab-case file name without extension |
| `{{ALIGNMENT}}` | Alignment string, e.g. `Neutral Evil`, `Unaligned` |
| `{{PB}}` | Proficiency bonus integer |
| `{{PASSIVE_PERCEPTION}}` | Calculated passive perception number |

## Notes

- `statblock: true` and `statblock-link: "#^statblock"` are always required.
- Omit Saving Throws, Skills, Damage Immunities, etc. if not applicable (remove those lines).
- Omit Bonus Actions and Reactions sections if none exist.
- The `^statblock` block ID must appear immediately after the closing ` ``` ` of the ad-statblock callout.
- The image path uses `3-Mechanics/CLI/bestiary/{{TYPE}}/img/` for lore images and `.../token/` for token images.
- Modifier calculation: `floor((score - 10) / 2)`, formatted as `(+N)` or `(-N)`.
