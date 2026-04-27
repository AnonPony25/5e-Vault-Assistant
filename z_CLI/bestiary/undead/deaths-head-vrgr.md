---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/vrgr
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/undead
aliases:
- "Death's Head"
---
# Death's Head
*Source: Van Richten's Guide to Ravenloft p. 232*  

A death's head is a disembodied, flying head. The type of creature one of these grotesque undead originated from determines how it terrorizes it prey. A death's head that arises from a person or animal swoops down to rip apart victims with its gnashing teeth. One with the head of monster like a nothic or medusa, though, retains a measure of the power it had in life and can befuddle the minds or petrify the bodies of its victims.

## Death's Head Tree

In cursed wilds grow death's head trees, awakened trees from which `2d6` death's heads dangle like foul fruit. The heads detach to protect the tree if it's threatened. Should the tree be destroyed, the heads scatter and plant themselves in unholy ground. A new death's head tree emerges from each planted head `1d12` months later.

## Statblock

```ad-statblock
title: Death's Head
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VRGR/Death%27s%20Head.webp#token)
*Tiny undead, Unaligned*

- **Armor Class** 16 (natural armor)
- **Hit Points** 17 (`5d4 + 5`)
- **Speed** 0 ft., fly 30 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 8 (-1)|13 (+1)|12 (+1)| 5 (-3)|14 (+2)| 3 (-4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** passive Perception 12
- **Damage Resistances** necrotic
- **Languages** —
- **Challenge** 1/2

## Traits

***Beheaded Form.*** When created, a death's head takes one of three forms: Aberrant Head, Gnashing Head, or Petrifying Head. This form determines the creature's attack.

***Unusual Nature.*** The death's head doesn't require air, food, drink, or sleep.

## Actions

***Gnashing Bite (Gnashing Head Only).*** *Melee Weapon Attack:* `+3` to hit, reach 5 ft., one target. *Hit:* 4 (`1d6 + 1`) piercing damage plus 7 (`2d6`) necrotic damage.

***Mind-Bending Bite (Aberrant Head Only).*** *Melee Weapon Attack:* `+3` to hit, reach 5 ft., one target. *Hit:* 4 (`1d6 + 1`) piercing damage plus 5 (`1d10`) necrotic damage, and the target must succeed on a DC 10 Intelligence saving throw or it can't take a reaction until the end of its next turn. Moreover, on its next turn, the target must choose whether it gets a move, an action, or a bonus action; it gets only one of the three.

***Petrifying Bite (Petrifying Head Only).*** *Melee Weapon Attack:* `+3` to hit, reach 5 ft., one target. *Hit:* 3 (`1d4 + 1`) piercing damage, and the target must succeed on a DC 10 Constitution saving throw or be [restrained](z_CLI/rules/conditions.md#Restrained) as it begins to turn to stone. The target must repeat the saving throw at the end of its next turn. On a success, the effect ends. On a failure, the target is [petrified](z_CLI/rules/conditions.md#Petrified) for 10 minutes.
```
^statblock