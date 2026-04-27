---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/idrotf
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
aliases:
- "Chardalyn Berserker"
---
# Chardalyn Berserker
*Source: Icewind Dale: Rime of the Frostmaiden p. 280*  

Chardalyn berserkers are Reghed nomads who wield weapons made of chardalyn, specifically ones suffused with demonic magic (see the sidebar on Chardalyn). This exposure has transformed them into fiends. They shed their heavier protective clothing and embrace the frigid cold, allowing frostbite to ravage the exposed parts of their bodies, with only their faith in the Frostmaiden keeping them alive.

## Chardalyn Weapons

A chardalyn berserker wields one or more weapons made wholly or partly out of chardalyn that has been tainted by demonic magic. Battleaxes, flails, javelins, and spears are favored weapons, though other weapons are possible.

A character who claims one or more of these weapons can be corrupted by them. Each day at dawn, roll a `d6` for each such weapon in the character's possession. On a roll of 1, the character must succeed on a DC 13 Charisma saving throw or become an evil NPC under the DM's control, unless the character is evil already. This alignment change can be undone by any magic that ends a curse, but after ten days, it can be reversed only by a [wish](z_CLI/spells/wish-xphb.md) spell or divine intervention.

A creature wounded by one of these chardalyn weapons can feel a sudden sickness creep over them, but it passes quickly.

## Chardalyn Madness

Prolonged contact with the demonic magic imprinted on the chardalyn has afflicted the berserker with a form of madness, causing the berserker to believe that its weapons are conduits through which it can speak to a demon lord or other dark power, as well as channel its rage. If the berserker's madness is cured using magic that removes the effects of madness, the berserker loses its Chardalyn Madness trait but retains its chaotic evil alignment and other qualities. Further exposure to the demonic magic causes the berserker's madness to return, however.

## Statblock

```ad-statblock
title: Chardalyn Berserker
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Chardalyn%20Berserker.webp#token)
*Medium fiend, Chaotic Evil*

- **Armor Class** 13 ([hide armor](z_CLI/items/hide-armor-xphb.md))
- **Hit Points** 90 (`12d8 + 36`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|12 (+1)|17 (+3)| 9 (-1)|11 (+0)| 9 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** [Survival](z_CLI/rules/skills.md#Survival) +4
- **Senses** passive Perception 10
- **Languages** any one language (usually Common)
- **Challenge** 4

## Traits

***Chardalyn Madness.*** The berserker must roll a `d6` at the start of each of its turns. On a 1, the berserker does nothing on its turn except speak to a nonexistent, evil master whom it has pledged to serve.

***Reckless.*** At the start of its turn, the berserker can gain advantage on all melee weapon attack rolls during that turn, but attack rolls against it have advantage until the start of its next turn.

## Actions

***Multiattack.*** The berserker attacks three times with a melee weapon.

***Chardalyn Flail.*** *Melee Weapon Attack:* `+5` to hit, reach 5 ft., one target. *Hit:* 7 (`1d8 + 3`) bludgeoning damage, and the target must succeed on a DC 13 Constitution saving throw or be [poisoned](z_CLI/rules/conditions.md#Poisoned) until the end of its next turn.

***Chardalyn Javelin.*** *Melee  or Ranged Weapon Attack:* `+5` to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 6 (`1d6 + 3`) piercing damage, and the target must succeed on a DC 13 Constitution saving throw or be [poisoned](z_CLI/rules/conditions.md#Poisoned) until the end of its next turn.
```
^statblock