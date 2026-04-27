---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/21
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/fiend/demon
aliases:
- "Molydeus"
---
# Molydeus
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 184, Mordenkainen's Tome of Foes p. 134*  

The fearsome molydeus speaks for the demon lord it serves and enforces its master's will. This demon is 12 feet tall, and its bipedal body has a slavering wolfs head and a fanged serpent's head. Its demon lord can speak and see through the serpent head; this master also uses the molydeus to guard treasures, slay foes, and terrify troops into obedience.

A molydeus' demon lord bestows on it a powerful weapon that dissolves if the molydeus dies. The weapon's form varies depending on the creator, but that doesn't affect the weapon's capabilities.

```ad-statblock
title: Molydeus
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Molydeus.webp#token)
*Huge fiend (demon), Typically  Chaotic Evil*

- **Armor Class** 19 (natural armor)
- **Hit Points** 216 (`16d12 + 112`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|28 (+9)|22 (+6)|25 (+7)|21 (+5)|24 (+7)|24 (+7)|

- **Proficiency Bonus** +7
- **Saving Throws** Strength +16, Constitution +14, Wisdom +14, Charisma +14
- **Skills** [Perception](z_CLI/rules/skills.md#Perception) +21
- **Senses** [truesight](z_CLI/rules/senses.md#Truesight) 120 ft., passive Perception 31
- **Damage Resistances** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [blinded](z_CLI/rules/conditions.md#Blinded), [charmed](z_CLI/rules/conditions.md#Charmed), [deafened](z_CLI/rules/conditions.md#Deafened), [frightened](z_CLI/rules/conditions.md#Frightened), [poisoned](z_CLI/rules/conditions.md#Poisoned), [stunned](z_CLI/rules/conditions.md#Stunned)
- **Languages** Abyssal, telepathy 120 ft.
- **Challenge** 21

## Traits

***Legendary Resistance (3/Day).*** If the molydeus fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** The molydeus has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The molydeus makes one Demonic Weapon attack, one Snakebite attack, and one Wolf Bite attack.

***Demonic Weapon.*** *Melee Weapon Attack:* `+16` to hit, reach 15 ft., one target. *Hit:* 35 (`4d12 + 9`) force damage. If the target has at least one head and the molydeus rolled a 20 on the attack roll, the target is decapitated and dies if it can't survive without that head. A target is immune to this effect if it takes none of the damage, has legendary actions, or is Huge or larger. Such a creature takes an extra 27 (`6d8`) force damage from the hit.

***Snakebite.*** *Melee Weapon Attack:* `+16` to hit, reach 15 ft., one creature. *Hit:* 16 (`2d6 + 9`) poison damage. The target must succeed on a DC 22 Constitution saving throw, or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target transforms into a [manes](z_CLI/bestiary/fiend/manes-xmm.md) if this reduces its hit point maximum to 0. This transformation can be ended only by a [wish](z_CLI/spells/wish-xphb.md) spell.

***Wolf Bite.*** *Melee Weapon Attack:* `+16` to hit, reach 10 ft., one target. *Hit:* 25 (`3d10 + 9`) necrotic damage.

***Spellcasting.*** The molydeus casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 22):

**At will:** [dispel magic](z_CLI/spells/dispel-magic-xphb.md), [polymorph](z_CLI/spells/polymorph-xphb.md), [telekinesis](z_CLI/spells/telekinesis-xphb.md), [teleport](z_CLI/spells/teleport-xphb.md)

**3/day:** [lightning bolt](z_CLI/spells/lightning-bolt-xphb.md)

## Legendary Actions

Legendary Action Uses: 3. Immediately after another creature's turn, the molydeus can expend a use to take one of the following actions. The molydeus regains all expended uses at the start of each of its turns.

***Attack.*** The molydeus makes one Demonic Weapon or Snakebite attack.

***Move.*** The molydeus moves without provoking [opportunity attacks](z_CLI/rules/actions.md#Opportunity%20Attack).

***Cast a Spell (Costs 2 Actions).*** The molydeus uses Spellcasting.
```
^statblock