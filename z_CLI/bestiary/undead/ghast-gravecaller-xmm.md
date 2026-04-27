---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
aliases:
- "Ghast Gravecaller"
---
# Ghast Gravecaller
*Source: Monster Manual (2024) p. 130*  

Ghast gravecallers wield fell magic and converse with corpses. They might pose as liches or vampires.

## Ghasts

*Tyrants among Corpses*

- **Habitat.** Swamp, Underdark, Urban  
- **Treasure.** Any  

Ghasts are reeking, undying corpses closely related to ghouls. They hunger for the vices they enjoyed in life as much as they do for rotting flesh.

## Statblock

```ad-statblock
title: Ghast Gravecaller
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Ghast%20Gravecaller.webp#token)
*Medium undead, Chaotic Evil*

- **Armor Class** 16
- **Hit Points** 97 (`15d8 + 30`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|17 (+3)|14 (+2)|18 (+4)|14 (+2)| 8 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +5, Wisdom +5
- **Skills** ⏤
- **Senses** [Darkvision](z_CLI/rules/senses.md#Darkvision) 120 ft., passive Perception 12
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](z_CLI/rules/conditions.md#Charmed), [exhaustion](z_CLI/rules/conditions.md#Exhaustion), [poisoned](z_CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common
- **Challenge** 6

## Traits

***Stench.*** *Constitution Saving Throw:* DC 13, any creature that starts its turn in a 5-foot [Emanation](z_CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from the ghast. *Failure:* The target has the [Poisoned](z_CLI/rules/conditions.md#Poisoned) condition until the start of its next turn. *Success:* The target is immune to this ghast's Stench for 24 hours.

## Actions

***Multiattack.*** The ghast makes two Horrific Necrosis attacks. It can replace one attack with a Claw attack.

***Claw.*** *Melee Attack Roll:* `+6`, reach 5 ft. *Hit:* 13 (`3d6 + 3`) Slashing damage. If the target isn't an Undead, it has the [Paralyzed](z_CLI/rules/conditions.md#Paralyzed) condition until the end of its next turn.

***Horrific Necrosis.*** *Melee  or Ranged Attack Roll:* `+7`, reach 5 ft. or range 120 ft. *Hit:* 15 (`2d10 + 4`) Necrotic damage, and the target has the [Frightened](z_CLI/rules/conditions.md#Frightened) condition until the end of its next turn.

***Spellcasting.*** The ghast casts one of the following spells, requiring no Material components and using Intelligence as the spellcasting ability:

**At will:** [Speak with Dead](z_CLI/spells/speak-with-dead-xphb.md), [Thaumaturgy](z_CLI/spells/thaumaturgy-xphb.md)
```
^statblock

## Environment

swamp, underdark, urban