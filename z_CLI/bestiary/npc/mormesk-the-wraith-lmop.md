---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/lmop
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
aliases:
- "Mormesk the Wraith"
---
# Mormesk the Wraith
*Source: Lost Mine of Phandelver p. 59*  

A wraith is the incorporeal remnant of a particularly hateful being. Most wraiths can transform those they have slain into spectral undead servitors. Mormesk chooses not to, preferring to let the dead stay dead.

```ad-statblock
title: Mormesk the Wraith
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/LMoP/Mormesk%20the%20Wraith.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 13
- **Hit Points** 45 (`6d8 + 18`)
- **Speed** 0 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|16 (+3)|16 (+3)|12 (+1)|14 (+2)|15 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** [darkvision](z_CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 12
- **Damage Resistances** acid; cold; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](z_CLI/rules/conditions.md#Charmed), [grappled](z_CLI/rules/conditions.md#Grappled), [paralyzed](z_CLI/rules/conditions.md#Paralyzed), [petrified](z_CLI/rules/conditions.md#Petrified), [poisoned](z_CLI/rules/conditions.md#Poisoned), [prone](z_CLI/rules/conditions.md#Prone), [restrained](z_CLI/rules/conditions.md#Restrained)
- **Languages** Common, Infernal
- **Challenge** 3

## Traits

***Incorporeal Movement.*** The wraith can move through an object or another creature, but can't stop there.

***Sunlight Sensitivity.*** While in sunlight, the wraith has disadvantage on attack rolls and on Wisdom ([Perception](z_CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Life Drain.*** *Melee Weapon Attack:* `+5` to hit, reach 5 ft., one creature. *Hit:* 16 (`3d8 + 3`) necrotic damage, and the target must succeed on a DC 13 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. If this attack reduces the target's hit point maximum to 0, the target dies. This reduction to the target's hit point maximum lasts until the target finishes a long rest.
```
^statblock