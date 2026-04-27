---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/cos
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/construct
aliases:
- "Broom of Animated Attack"
---
# Broom of Animated Attack
*Source: Curse of Strahd p. 226*  

A broom of animated attack is easily mistaken for a broom of flying. It attacks any creature that grabs it or tries to ride it.

## Flying Broom

Some brooms of animated attack allow their creators to ride them, in which case they behave like typical brooms of flying. A broom of animated attack, however, can carry only half the weight that a broom of flying can (see chapter 7, "Treasure," of the Dungeon Master's Guide).

## Statblock

```ad-statblock
title: Broom of Animated Attack
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoS/Broom%20of%20Animated%20Attack.webp#token)
*Small construct, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 17 (`5d6`)
- **Speed** 0 ft., fly 50 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|17 (+3)|10 (+0)| 1 (-5)| 5 (-3)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** [blindsight](z_CLI/rules/senses.md#Blindsight) 30 ft. (blind beyond this radius), passive Perception 7
- **Damage Immunities** poison, psychic
- **Condition Immunities** [blinded](z_CLI/rules/conditions.md#Blinded), [charmed](z_CLI/rules/conditions.md#Charmed), [deafened](z_CLI/rules/conditions.md#Deafened), [exhaustion](z_CLI/rules/conditions.md#Exhaustion), [frightened](z_CLI/rules/conditions.md#Frightened), [paralyzed](z_CLI/rules/conditions.md#Paralyzed), [petrified](z_CLI/rules/conditions.md#Petrified), [poisoned](z_CLI/rules/conditions.md#Poisoned), [prone](z_CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 1/4

## Traits

***Constructed Nature.*** An animated object doesn't require air, food, drink, or sleep.

The magic that animates an object is dispelled when the construct drops to 0 hit points. An animated object reduced to 0 hit points becomes inanimate and is too damaged to be of much use or value to anyone.

***Antimagic Susceptibility.*** The broom is [incapacitated](z_CLI/rules/conditions.md#Incapacitated) while in the area of an [antimagic field](z_CLI/spells/antimagic-field-xphb.md). If targeted by [dispel magic](z_CLI/spells/dispel-magic-xphb.md), the broom must succeed on a Constitution saving throw against the caster's spell save DC or fall [unconscious](z_CLI/rules/conditions.md#Unconscious) for 1 minute.

***False Appearance.*** While the broom remains motionless and isn't flying, it is indistinguishable from a normal broom.

## Actions

***Multiattack.*** The broom makes two melee attacks.

***Broomstick.*** *Melee Weapon Attack:* `+5` to hit, reach 5 ft., one target. *Hit:* 5 (`1d4 + 3`) bludgeoning damage.

## Reactions

***Animated Attack.*** If the broom is motionless and a creature grabs hold of it, the broom makes a Dexterity check contested by the creature's Strength check. If the broom wins the contest, it flies out of the creature's grasp and makes a melee attack against it with advantage on the attack roll.
```
^statblock