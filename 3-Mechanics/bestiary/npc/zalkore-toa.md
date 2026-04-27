---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/toa
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
aliases:
- "Zalkoré"
---
# Zalkoré
*Source: Tomb of Annihilation p. 79*  

```ad-statblock
title: Zalkoré
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Zalkore.webp#token)
*Medium monstrosity, Lawful Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 127 (`17d8 + 51`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|15 (+2)|16 (+3)|12 (+1)|13 (+1)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** [Deception](z_CLI/rules/skills.md#Deception) +5, [Insight](z_CLI/rules/skills.md#Insight) +4, [Perception](z_CLI/rules/skills.md#Perception) +4, [Stealth](z_CLI/rules/skills.md#Stealth) +5
- **Senses** [darkvision](z_CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 14
- **Gear** [longbow](z_CLI/items/longbow-xphb.md), [shortsword](z_CLI/items/shortsword-xphb.md)
- **Languages** Common
- **Challenge** 6

## Traits

***Petrifying Gaze.*** When a creature that can see Zalkoré's eyes starts its turn within 30 feet of Zalkoré, Zalkoré can force it to make a DC 14 Constitution saving throw if Zalkoré isn't [incapacitated](z_CLI/rules/conditions.md#Incapacitated) and can see the creature. If the saving throw fails by 5 or more, the creature is instantly [petrified](z_CLI/rules/conditions.md#Petrified). Otherwise, a creature that fails the save begins to turn to stone and is [restrained](z_CLI/rules/conditions.md#Restrained). The [restrained](z_CLI/rules/conditions.md#Restrained) creature must repeat the saving throw at the end of its next turn, becoming [petrified](z_CLI/rules/conditions.md#Petrified) on a failure or ending the effect on a success. The petrification lasts until the creature is freed by the  [greater restoration](z_CLI/spells/greater-restoration-xphb.md) spell or other magic.

Unless [surprised](z_CLI/rules/conditions.md#Surprised), a creature can avert its eyes to avoid the saving throw at the start of its turn. If the creature does so, it can't see Zalkoré until the start of its next turn, when it can avert its eyes again. If the creature looks at Zalkoré in the meantime, it must immediately make the save.

If Zalkoré sees itself reflected on a polished surface within 30 feet of it and in an area of bright light, Zalkoré is, due to its curse, affected by its own gaze.

## Actions

***Multiattack.*** Zalkoré makes either three melee attacks—one with its snake hair and two with its shortsword—or two ranged attacks with its longbow.

***Snake Hair.*** *Melee Weapon Attack:* `+5` to hit, reach 5 ft., one creature. *Hit:* 4 (`1d4 + 2`) piercing damage plus 14 (`4d6`) poison damage.

***Shortsword.*** *Melee Weapon Attack:* `+5` to hit, reach 5 ft., one target. *Hit:* 5 (`1d6 + 2`) piercing damage.

***Longbow.*** *Ranged Weapon Attack:* `+5` to hit, range 150/600 ft., one target. *Hit:* 6 (`1d8 + 2`) piercing damage plus 7 (`2d6`) poison damage.
```
^statblock