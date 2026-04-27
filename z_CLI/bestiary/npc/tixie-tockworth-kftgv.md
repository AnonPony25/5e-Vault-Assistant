---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/kftgv
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/gnome
aliases:
- "Tixie Tockworth"
---
# Tixie Tockworth
*Source: Keys from the Golden Vault p. 85*  

Using magic and mechanical know-how, Tixie Tockworth has transformed most of herself into a machine. What was once her torso is now a steel carapace that can discharge jets of scalding steam. Her left arm ends in a humming blade. Her right arm ends in a metal shield. Her eyes are shiny, metallic red orbs that can see through illusions.

In her current form, Tockworth ruthlessly seeks to destroy anyone and anything that stands in the way of her ultimate goal, which is to become a Construct. If she's allowed to continue her work, she will achieve this apotheosis in a matter of weeks, after which her creature type changes to Construct. She also gains immunity to poison damage, as well as immunity to the paralyzed, petrified, and poisoned conditions. Her statistics are otherwise unchanged.

```ad-statblock
title: Tixie Tockworth
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/KftGV/Tixie%20Tockworth.webp#token)
*Small humanoid (gnome), Chaotic Evil*

- **Armor Class** 17 (natural armor, [shield](z_CLI/items/shield-xphb.md))
- **Hit Points** 75 (`10d6 + 40`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|13 (+1)|18 (+4)|17 (+3)| 9 (-1)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +6, Wisdom +2
- **Skills** [Arcana](z_CLI/rules/skills.md#Arcana) +9, [Perception](z_CLI/rules/skills.md#Perception) +2
- **Senses** [truesight](z_CLI/rules/senses.md#Truesight) 60 ft., passive Perception 12
- **Gear** [shortsword](z_CLI/items/shortsword-xphb.md)
- **Languages** Common, Gnomish, Terran, Undercommon
- **Challenge** 7

## Traits

***Force Field.*** Tockworth generates a magical force field around herself. This force field has 15 hit points and regains all its hit points at the start of each of Tockworth's turns, but it ceases to function if Tockworth drops to 0 hit points. Any damage Tockworth takes is subtracted from the force field's hit points first. Each time the force field regains hit points, the following conditions end on Tockworth: [grappled](z_CLI/rules/conditions.md#Grappled), [restrained](z_CLI/rules/conditions.md#Restrained), and [stunned](z_CLI/rules/conditions.md#Stunned).

## Actions

***Multiattack.*** Tockworth makes three Shortsword or Lightning Discharge attacks.

***Shortsword.*** *Melee Weapon Attack:* `+6` to hit, reach 5 ft., one target. *Hit:* 6 (`1d6 + 3`) piercing damage plus 10 (`3d6`) force damage.

***Lightning Discharge.*** *Ranged Spell Attack:* `+6` to hit, range 60 ft., one creature. *Hit:* 16 (`3d10`) lightning damage.

***Spellcasting.*** Tockworth casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 14):

**At will:** [nondetection](z_CLI/spells/nondetection-xphb.md) (self only)

**2/day:** [dimension door](z_CLI/spells/dimension-door-xphb.md)

**1/day each:** [blindness/deafness](z_CLI/spells/blindness-deafness-xphb.md), [blur](z_CLI/spells/blur-xphb.md)

## Bonus Actions

***Scalding Steam (Recharge 5-6).*** Tockworth emits a jet of piping-hot steam in a 15-foot cone. Each creature in that cone must make a DC 15 Dexterity saving throw, taking 10 (`3d6`) fire damage on a failed save, or half as much damage on a successful one.
```
^statblock