---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/toa
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
aliases:
- "Clay Gladiator"
---
# Clay Gladiator
*Source: Tomb of Annihilation p. 100*  

A clay gladiator fights if attacked or when called to the gladiatorial pit. If reduced to 0 hit points outside of the gladiatorial pit, the gladiator disappears along with its possessions, reappears in its cell at full health with spear and shield in hand, and returns to the gladiatorial pit if it can. If defeated in the gladiatorial pit, the gladiator leaves its spear behind before reforming in its cell

```ad-statblock
title: Clay Gladiator
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Clay%20Gladiator.webp#token)
*Medium construct, Unaligned*

- **Armor Class** 17 (natural armor, [shield](z_CLI/items/shield-xphb.md))
- **Hit Points** 112 (`15d8 + 45`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|15 (+2)|16 (+3)|10 (+0)|12 (+1)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +7, Dexterity +5, Constitution +6
- **Skills** [Athletics](z_CLI/rules/skills.md#Athletics) +10, [Intimidation](z_CLI/rules/skills.md#Intimidation) +5
- **Senses** passive Perception 11
- **Damage Immunities** poison
- **Condition Immunities** [charmed](z_CLI/rules/conditions.md#Charmed), [frightened](z_CLI/rules/conditions.md#Frightened), [poisoned](z_CLI/rules/conditions.md#Poisoned)
- **Gear** [spear](z_CLI/items/spear-xphb.md)
- **Languages** —
- **Challenge** 5

## Traits

***Climbing.*** The gladiator can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Steadfast.*** The gladiator can't be disarmed, and cannot make ranged attacks.

***Brute.*** A melee weapon deals one extra die of its damage when the gladiator hits with it (included in the attack).

## Actions

***Multiattack.*** The gladiator makes three melee attacks.

***Spear.*** *Melee Weapon Attack:* `+7` to hit, reach 5 ft., one target. *Hit:* 11 (`2d6 + 4`) piercing damage, or 13 (`2d8 + 4`) piercing damage if used with two hands.

***Shield Bash.*** *Melee Weapon Attack:* `+7` to hit, reach 5 ft., one creature. *Hit:* 9 (`2d4 + 4`) bludgeoning damage. If the target is a Medium or smaller creature, it must succeed on a DC 15 Strength saving throw or be knocked [prone](z_CLI/rules/conditions.md#Prone).

## Reactions

***Parry.*** The gladiator adds 3 to its AC against one melee attack that would hit it. To do so, the gladiator must see the attacker and be wielding a melee weapon.
```
^statblock