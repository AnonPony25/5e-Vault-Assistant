---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/idrotf
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/undead
aliases:
- "Kobold Vampire Spawn"
---
# Kobold Vampire Spawn
*Source: Icewind Dale: Rime of the Frostmaiden p. 297*  

The gnoll vampire Tekeli-li has a small number of kobold vampire spawn minions to keep it company in the Caves of Hunger (see chapter 6). The vampiric kobolds are terrified of the gnoll vampire and can't understand its commands, so they give Tekeli-li a wide berth. These ravenous undead kobolds thirst for blood and tend to swarm one foe at a time.

```ad-statblock
title: Kobold Vampire Spawn
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Kobold%20Vampire%20Spawn.webp#token)
*Small undead, Neutral Evil*

- **Armor Class** 14
- **Hit Points** 39 (`6d6 + 18`)
- **Speed** 30 ft., climb 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|18 (+4)|16 (+3)| 8 (-1)| 8 (-1)| 8 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** Dexterity +6, Wisdom +1
- **Skills** [Perception](z_CLI/rules/skills.md#Perception) +1, [Stealth](z_CLI/rules/skills.md#Stealth) +6
- **Senses** [darkvision](z_CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 11
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
- **Languages** Common, Draconic
- **Challenge** 3

## Traits

***Pack Tactics.*** The vampire has advantage on an attack roll against a creature if at least one of the vampire's allies is within 5 feet of the creature and the ally isn't [incapacitated](z_CLI/rules/conditions.md#Incapacitated).

***Regeneration.*** The vampire regains 10 hit points at the start of its turn if it has at least 1 hit point and isn't in sunlight or running water. If the vampire takes radiant damage or damage from [holy water](z_CLI/items/holy-water-xphb.md), this trait doesn't function at the start of its next turn.

***Unusual Nature.*** The vampire doesn't require air.

***Vampire Weaknesses.*** The vampire has the following flaws:

- **Forbiddance.** The vampire can't enter a residence without an invitation from one of the occupants.  
- **Harmed by Running Water.** The vampire takes 20 acid damage when it starts its turn in running water.  
- **Stake to the Heart.** The vampire is destroyed if a piercing weapon made of wood is driven into its heart while it is [incapacitated](z_CLI/rules/conditions.md#Incapacitated) in its resting place.  
- **Sunlight Hypersensitivity.** The vampire takes 20 radiant damage when it starts its turn in sunlight. While in sunlight, it has disadvantage on attack rolls and ability checks.  

## Actions

***Bite.*** *Melee Weapon Attack:* `+6` to hit, reach 5 ft., one creature. *Hit:* 6 (`1d4 + 4`) piercing damage plus 5 (`2d4`) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and the vampire regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0.
```
^statblock