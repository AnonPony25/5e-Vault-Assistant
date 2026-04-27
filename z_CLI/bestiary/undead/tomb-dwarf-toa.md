---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/toa
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
aliases:
- "Tomb Dwarf"
---
# Tomb Dwarf
*Source: Tomb of Annihilation p. 135*  

Acererak abducted dwarf miners and transformed them into wights to exploit their expertise at underground construction.

```ad-statblock
title: Tomb Dwarf
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Tomb%20Dwarf.webp#token)
*Medium undead, Lawful Evil*

- **Armor Class** 14 ([studded leather](z_CLI/items/studded-leather-armor-xphb.md))
- **Hit Points** 45 (`6d8 + 18`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|14 (+2)|16 (+3)|10 (+0)|13 (+1)|15 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** [Perception](z_CLI/rules/skills.md#Perception) +3, [Stealth](z_CLI/rules/skills.md#Stealth) +4
- **Senses** [darkvision](z_CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 13
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](z_CLI/rules/conditions.md#Exhaustion), [poisoned](z_CLI/rules/conditions.md#Poisoned)
- **Gear** [battleaxe](z_CLI/items/battleaxe-xphb.md), [light crossbow](z_CLI/items/light-crossbow-xphb.md)
- **Languages** the languages it knew in life
- **Challenge** 3

## Traits

***Sunlight Sensitivity.*** While in sunlight, the tomb dwarf has disadvantage on attack rolls, as well as on Wisdom ([Perception](z_CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Multiattack.*** The tomb dwarf makes two longsword attacks or two crossbow attacks. It can use its Life Drain in place of one longsword attack.

***Life Drain.*** *Melee Weapon Attack:* `+4` to hit, reach 5 ft., one creature. *Hit:* 5 (`1d6 + 2`) necrotic damage. The target must succeed on a DC 13 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.A humanoid slain by this attack rises 24 hours later as a zombie under the tomb dwarf's control, unless the humanoid is restored to life or its body is destroyed. The tomb dwarf can have no more than twelve zombies under its control at one time.

***Battleaxe.*** *Melee Weapon Attack:* `+4` to hit, reach 5 ft., one target. *Hit:* 6 (`1d8 + 2`) slashing damage, or 7 (`1d10 + 2`) slashing damage if used with two hands.

***Light Crossbow.*** *Ranged Weapon Attack:* `+4` to hit, range 80/320 ft., one target. *Hit:* 6 (`1d8 + 2`) piercing damage.
```
^statblock