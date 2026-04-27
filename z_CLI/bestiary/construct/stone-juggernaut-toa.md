---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/toa
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
aliases:
- "Stone Juggernaut"
---
# Stone Juggernaut
*Source: Tomb of Annihilation p. 231*  

A stone juggernaut is a rolling construct imbued with enough awareness to avoid obvious dangers such as open pits and chasms. It trundles across open battlefields or rolls down dungeon corridors, crushing anyone in its path. Every stone juggernaut has a unique shape and appearance. One might resemble an elephant with bejeweled tusks, while another might look like a scowling demon with flaming eyes and obsidian teeth.

A stone juggernaut is fast, but it lacks maneuverability and can move in only one direction on its turn. It poses little danger to creatures it can't crush beneath its rollers. Its best tactic is to slam into a creature, knock it [prone](z_CLI/rules/conditions.md#Prone), and then roll over it.

```ad-statblock
title: Stone Juggernaut
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Stone%20Juggernaut.webp#token)
*Large construct, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 157 (`15d10 + 75`)
- **Speed** 50 ft. (in one direction chosen at the start of its turn)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|12 (+1)|15 (+2)|14 (+2)|14 (+2)|16 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** [blindsight](z_CLI/rules/senses.md#Blindsight) 120 ft., passive Perception 10
- **Damage Immunities** poison; bludgeoning, piercing, slashing from nonmagical attacks not made with adamantine weapons
- **Condition Immunities** [blinded](z_CLI/rules/conditions.md#Blinded), [charmed](z_CLI/rules/conditions.md#Charmed), [deafened](z_CLI/rules/conditions.md#Deafened), [exhaustion](z_CLI/rules/conditions.md#Exhaustion), [frightened](z_CLI/rules/conditions.md#Frightened), [paralyzed](z_CLI/rules/conditions.md#Paralyzed), [petrified](z_CLI/rules/conditions.md#Petrified), [poisoned](z_CLI/rules/conditions.md#Poisoned), [prone](z_CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 12

## Traits

***Devastating Roll.*** The juggernaut can move through the space of a [prone](z_CLI/rules/conditions.md#Prone) creature. A creature whose space the juggernaut enters for the first time on a turn must make a DC 17 Dexterity saving throw, taking 55 (`10d10`) bludgeoning damage on a failed save, or half as much damage on a successful one.

***Immutable Form.*** The juggernaut is immune to any spell or effect that would alter its form.

***Regeneration.*** As long as it has 1 hit point left, the juggernaut magically regains all its hit points daily at dawn. The juggernaut is destroyed and doesn't regenerate if it drops to 0 hit points.

***Siege Monster.*** The juggernaut deals double damage to objects and structures.

## Actions

***Slam.*** *Melee Weapon Attack:* `+10` to hit, reach 5 ft., one target. *Hit:* 25 (`3d12 + 6`) bludgeoning damage. If the target is a Large or smaller creature, it must succeed on a DC 17 Strength saving throw or be knocked [prone](z_CLI/rules/conditions.md#Prone).
```
^statblock