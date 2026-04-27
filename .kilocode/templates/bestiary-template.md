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
