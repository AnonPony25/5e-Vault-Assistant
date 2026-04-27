---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/toa
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/undead
aliases:
- "Tyrannosaurus Zombie"
---
# Tyrannosaurus Zombie
*Source: Tomb of Annihilation p. 241*  

A tyrannosaurus zombie has a gullet full of smaller zombies, which it can disgorge. These zombies aren't under the tyrannosaurus zombie's control.

```ad-statblock
title: Tyrannosaurus Zombie
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Tyrannosaurus%20Zombie.webp#token)
*Huge undead, Unaligned*

- **Armor Class** 11 (natural armor)
- **Hit Points** 136 (`13d12 + 52`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|25 (+7)| 6 (-2)|19 (+4)| 1 (-5)| 3 (-4)| 5 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** [darkvision](z_CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 6
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](z_CLI/rules/conditions.md#Poisoned)
- **Languages** —
- **Challenge** 8

## Traits

***Disgorge Zombie.*** As a bonus action, the tyrannosaurus zombie can disgorge a normal [zombie](z_CLI/bestiary/undead/zombie-xmm.md), which appears in an unoccupied space within 10 feet of it. The disgorged [zombie](z_CLI/bestiary/undead/zombie-xmm.md) acts on its own initiative count. After a zombie is disgorged, roll a `d6`. On a roll of 1, the tyrannosaurus zombie runs out of zombies to disgorge and loses this trait. If the tyrannosaurus zombie still has this trait when it dies, `1d4` normal zombies erupt from its corpse at the start of its next turn. These zombies act on their own initiative count.

***Undead Fortitude.*** If damage reduces the tyrannosaurus zombie to 0 hit points, it must make a Constitution saving throw with a DC of 5+the damage taken, unless the damage is radiant or from a critical hit. On a success, the zombie drops to 1 hit point instead.

## Actions

***Multiattack.*** The tyrannosaurus zombie makes two attacks: one with its bite and one with its tail. It can't make both attacks against the same target.

***Bite.*** *Melee Weapon Attack:* `+10` to hit, reach 10 ft., one target. *Hit:* 33 (`4d12 + 7`) piercing damage. If the target is a Medium or smaller creature, it is [grappled](z_CLI/rules/conditions.md#Grappled) (escape DC 17). Until this grapple ends, the target is [restrained](z_CLI/rules/conditions.md#Restrained) and the tyrannosaurus zombie can't bite another target or disgorge zombies.

***Tail.*** *Melee Weapon Attack:* `+10` to hit, reach 10 ft., one target. *Hit:* 20 (`3d8 + 7`) bludgeoning damage.
```
^statblock