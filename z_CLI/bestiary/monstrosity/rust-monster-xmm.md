---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
aliases:
- "Rust Monster"
---
# Rust Monster
*Source: Monster Manual (2024) p. 263. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Rust Monster

*Corrosive, Equipment-Eating Scavenger*

- **Habitat.** Underdark  
- **Treasure.** None  

Rust monsters roam the Underdark searching for ferrous metal. When they find this material—whether natural veins, subterranean structures, or creatures' equipment—these beetle-like scavengers rush to feed. Using their feathery antennae, rust monsters dissolve metals such as iron and steel into rusted scrap. They easily gnaw through this corroded metal using their mandibles. Rust monsters usually ignore creatures without metal equipment, but they defend themselves if attacked.

```ad-statblock
title: Rust Monster
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Rust%20Monster.webp#token)
*Medium monstrosity, Unaligned*

- **Armor Class** 14
- **Hit Points** 33 (`6d8 + 6`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|12 (+1)|13 (+1)| 2 (-4)|13 (+1)| 6 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** [Darkvision](z_CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 11
- **Languages** —
- **Challenge** 1/2

## Traits

***Iron Scent.*** The rust monster can pinpoint the location of ferrous metal within 30 feet of itself.

## Actions

***Multiattack.*** The rust monster makes one Bite attack and uses Antennae twice.

***Bite.*** *Melee Attack Roll:* `+3`, reach 5 ft. *Hit:* 5 (`1d8 + 1`) Piercing damage.

***Antennae.*** The rust monster targets one nonmagical metal object—armor or a weapon—worn or carried by a creature within 5 feet of itself. *Dexterity Saving Throw:* DC 11, the creature with the object. *Failure:* The object takes a -1 penalty to the AC it offers (armor) or to its attack rolls (weapon). Armor is destroyed if the penalty reduces its AC to 10, and a weapon is destroyed if its penalty reaches -5. The penalty can be removed by casting the [Mending](z_CLI/spells/mending-xphb.md) spell on the armor or weapon.

***Destroy Metal.*** The rust monster touches a nonmagical metal object within 5 feet of itself that isn't being worn or carried. The touch destroys a 1-foot [Cube](z_CLI/rules/variant-rules/cube-area-of-effect-xphb.md) of the object.

## Reactions

***Reflexive Antennae.*** Trigger: An attack roll hits the rust monster. _Response:_ The rust monster uses Antennae.
```
^statblock

## Environment

underdark