---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/lower
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
aliases:
- "Succubus"
---
# Succubus
*Source: Monster Manual (2024) p. 303. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Succubus

*Life-Draining Seducer*

- **Habitat.** Planar (Lower Planes), Urban  
- **Treasure.** [Implements](z_CLI/tables/random-magic-items-implements.md)  

Succubi prey on mortals physically and exploit their waking desires. They relish corrupting virtuous souls and the pain an individual's downfall can cause. Once their targets are at their lowest, succubi slay their victims with their essence-draining kiss.

Through fiendish rites, succubi can transform into incubi to manipulate their prey in dreams as well as the waking world. They can also change shape to torment their victims. These tempters can dominate Humanoids, but they usually do so to reinforce their manipulations or defend themselves rather than controlling others outright. Roll on or choose a result from the Succubus Temptations table to inspire how a succubus toys with its victims.

**Succubus Temptations**

| dice: 1d6 | The Succubus Manipulates Its Target By... |
|-----------|-------------------------------------------|
| 1 | Adopting the form of a lost loved one. |
| 2 | Charming someone close to its target. |
| 3 | Isolating them from their loved ones. |
| 4 | Manipulating events to bring surprise fortune. |
| 5 | Posing as a flattering underling. |
| 6 | Taking the form of one in need of protection. |
^succubus-temptations

```ad-statblock
title: Succubus
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Succubus.webp#token)
*Medium fiend, Neutral Evil*

- **Armor Class** 15
- **Hit Points** 71 (`13d8 + 13`)
- **Speed** 30 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 8 (-1)|17 (+3)|13 (+1)|15 (+2)|12 (+1)|20 (+5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** [Deception](z_CLI/rules/skills.md#Deception) +9, [Insight](z_CLI/rules/skills.md#Insight) +5, [Perception](z_CLI/rules/skills.md#Perception) +5, [Persuasion](z_CLI/rules/skills.md#Persuasion) +9, [Stealth](z_CLI/rules/skills.md#Stealth) +7
- **Senses** [Darkvision](z_CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 15
- **Damage Resistances** cold, fire, poison, psychic
- **Languages** Abyssal, Common, Infernal; telepathy 60 ft.
- **Challenge** 4

## Traits

***Incubus Form.*** When the succubus finishes a [Long Rest](z_CLI/rules/variant-rules/long-rest-xphb.md), it can shape-shift into an [Incubus](z_CLI/bestiary/fiend/incubus-xmm.md), using that stat block instead of this one.

## Actions

***Multiattack.*** The succubus makes one Fiendish Touch attack and uses Charm or Draining Kiss.

***Fiendish Touch.*** *Melee Attack Roll:* `+7`, reach 5 ft. *Hit:* 16 (`2d10 + 5`) Psychic damage.

***Charm.*** The succubus casts [Dominate Person](z_CLI/spells/dominate-person-xphb.md) (level 8 version), requiring no spell components and using Charisma as the spellcasting ability (spell save DC 15).

***Draining Kiss.*** *Constitution Saving Throw:* DC 15, one creature [Charmed](z_CLI/rules/conditions.md#Charmed) by the succubus within 5 feet. *Failure:* 13 (`3d8`) Psychic damage. *Success:* Half damage. *Failure or Success:* The target's [Hit Point](z_CLI/rules/variant-rules/hit-points-xphb.md) maximum decreases by an amount equal to the damage taken.

## Bonus Actions

***Shape-Shift.*** The succubus shape-shifts to resemble a Medium or Small Humanoid or back into its true form. Its game statistics are the same in each form, except its [Fly Speed](z_CLI/rules/variant-rules/fly-speed-xphb.md) is available only in its true form. Any equipment it's wearing or carrying isn't transformed.
```
^statblock

## Environment

planar, lower, urban