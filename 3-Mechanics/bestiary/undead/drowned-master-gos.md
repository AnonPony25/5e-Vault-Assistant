---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/gos
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
aliases:
- "Drowned Master"
---
# Drowned Master
*Source: Ghosts of Saltmarsh p. 235*  

This waterlogged undead, bound to the Pit of Hatred in Tammeraut's Fate, hovers menacingly over the bones of its victims. Its torso, arms, and head retain their former shapes, but its legs have split into shadowy tentacles. The drowned master is tethered to a source of powerful magic that prevents it from traveling far. It commands other drowned ones, compelling them to serve as agents in its dark plots.

## Bluerot

This disease targets humanoids. While afflicted with bluerot, a victim grows grotesque blue boils on their face and back. This disease is carried by undead (including the drowned ones in Tammeraut's Fate), and victims most often acquire it through wounds caused by infected creatures. The disease's boils manifest in `1d4` hours, causing the victim's Constitution and Charisma scores to decrease by `1d4` each, to a minimum of 3. This is quickly followed by a fever and tingling in the extremities. An infected creature is vulnerable to radiant damage and gains the ability to breathe underwater.

At the end of each long rest, an infected creature makes a DC 12 Constitution saving throw. On a success, the victim regains 1 point of Constitution and 1 point of Charisma lost to the disease. If the infected creature regains all the points lost to the disease, it is cured. Other effects that raise the victim's ability scores do not cure the disease. On a failed saving throw, the victim takes 18 (`4d8`) necrotic damage as the boils burst and spread. A creature reduced to 0 hit points by this damage cannot regain hit points until the disease is cured, though it can be stabilized as normal.

## Statblock

```ad-statblock
title: Drowned Master
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GoS/Drowned%20Master.webp#token)
*Medium undead, Chaotic Evil*

- **Armor Class** 14 (natural armor)
- **Hit Points** 157 (`21d8 + 63`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)|12 (+1)|16 (+3)| 9 (-1)|14 (+2)|12 (+1)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +7, Wisdom +6
- **Skills** [Perception](z_CLI/rules/skills.md#Perception) +10
- **Senses** [darkvision](z_CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 20
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](z_CLI/rules/conditions.md#Poisoned)
- **Gear** [greatsword](z_CLI/items/greatsword-xphb.md)
- **Languages** understands the languages it knew in life but can't speak
- **Challenge** 9

## Traits

***Bound Together.*** The drowned master shares its mind with every other drowned one within 1 mile of it, and can communicate its thoughts and observations to them instantaneously and without limitation.

***Cold Aura.*** At the start of each of the drowned master's turns, each creature within 5 feet of it takes 5 (`1d10`) cold damage. A creature that touches the drowned master or hits it with a melee attack while within 5 feet of it takes 5 (`1d10`) cold damage.

***Undead Fortitude.*** If damage reduces the drowned master to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the drowned master drops to 1 hit point instead.

## Actions

***Multiattack.*** The drowned master makes two attacks: one with its greatsword and one with its Life-Draining Tentacle.

***Greatsword.*** *Melee Weapon Attack:* `+7` to hit, reach 5 ft., one target. *Hit:* 10 (`2d6 + 3`) slashing damage plus 14 (`4d6`) cold damage, and the target must succeed on a DC 12 Constitution saving throw or contract [bluerot](z_CLI/rules/diseases.md#Bluerot) (see the "Bluerot" in notes).

***Life-Draining Tentacle.*** *Melee Weapon Attack:* `+7` to hit, reach 15 ft., one target. *Hit:* 10 (`2d6 + 3`) necrotic damage. The target must succeed on a DC 15 Constitution saving throw or have its hit point maximum reduced by an amount equal to the damage taken. The target dies if this effect reduces its hit point maximum to 0. This reduction lasts until the target finishes a long rest. On a failed save, the target also contracts bluerot (see the "Bluerot" in notes).

***Necrotic Ink (Recharge 5-6).*** The drowned master discharges foul ink in front of itself in a 30-foot cone. Each creature caught in the ink must make a DC 15 Constitution saving throw, taking 27 (`6d8`) necrotic damage on a failed save or half as much damage on a successful one. A creature that fails this saving throw is [blinded](z_CLI/rules/conditions.md#Blinded) until the end of its next turn and contracts bluerot (see the "Bluerot" in notes).
```
^statblock