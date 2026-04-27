---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/idrotf
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/aberration
aliases:
- "Gnome Ceremorph"
---
# Gnome Ceremorph
*Source: Icewind Dale: Rime of the Frostmaiden p. 303*  

Mind flayers, which are described in the Monster Manual, are created through ceremorphosis, a process that begins with the implantation of an illithid tadpole in the brain of a humanoid host. After about seven days in its new home, the tadpole transforms its host into a mind flayer. The new creation typically retains no memory of its previous existence.

For reasons unknown, ceremorphosis can go awry when an illithid tadpole is implanted in the brain of a gnome. This deviation might be due to the quasi-magical nature of gnomes, or simply a facet of how their minds work. When the process is warped only slightly, the mind flayer remains gnome-sized and is called a gnome ceremorph. It retains its knowledge of the Gnomish language while becoming able to speak Deep Speech and Undercommon. It retains fragmented memories of its previous life and previous alignment, not to mention a propensity for invention.

## Laser Pistol

A gnome ceremorph often carries a home-built device that functions as a [laser pistol](z_CLI/items/laser-pistol-xdmg.md) (see ""Firearms"" in the "Dungeon Master's Guide"). This weapon is powered by an [energy cell](z_CLI/items/energy-cell-xdmg.md), which enables the weapon to fire 50 shots. After its last shot is expended, the device becomes inoperable. The [energy cell](z_CLI/items/energy-cell-xdmg.md) can't be removed without destroying the weapon.

## Statblock

```ad-statblock
title: Gnome Ceremorph
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Gnome%20Ceremorph.webp#token)
*Small aberration, Any alignment*

- **Armor Class** 16 ([breastplate](z_CLI/items/breastplate-xphb.md))
- **Hit Points** 58 (`13d6 + 13`)
- **Speed** 25 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|14 (+2)|12 (+1)|19 (+4)|17 (+3)|17 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +7, Wisdom +6, Charisma +6
- **Skills** [Arcana](z_CLI/rules/skills.md#Arcana) +7, [Deception](z_CLI/rules/skills.md#Deception) +6, [Insight](z_CLI/rules/skills.md#Insight) +6, [Perception](z_CLI/rules/skills.md#Perception) +6, [Persuasion](z_CLI/rules/skills.md#Persuasion) +6, [Stealth](z_CLI/rules/skills.md#Stealth) +5
- **Senses** [darkvision](z_CLI/rules/senses.md#Darkvision) 120 ft., passive Perception 16
- **Gear** [laser pistol](z_CLI/items/laser-pistol-xdmg.md)
- **Languages** Deep Speech, Gnomish, telepathy 120 ft., Undercommon
- **Challenge** 5

## Traits

***Innate Spellcasting (Psionics).*** The ceremorph's innate spellcasting ability is Intelligence (spell save DC 15). It can innately cast the following spells, requiring no components:

**At will:** [detect thoughts](z_CLI/spells/detect-thoughts-xphb.md), [levitate](z_CLI/spells/levitate-xphb.md)

**1/day each:** [dominate monster](z_CLI/spells/dominate-monster-xphb.md), [plane shift](z_CLI/spells/plane-shift-xphb.md) (self only)

***Magic Resistance.*** The ceremorph has advantage on saving throws against spells and other magical effects.

## Actions

***Tentacles.*** *Melee Weapon Attack:* `+7` to hit, reach 5 ft., one creature. *Hit:* 15 (`2d10 + 4`) psychic damage. If the target is Medium or smaller, it is [grappled](z_CLI/rules/conditions.md#Grappled) (escape DC 9) and must succeed on a DC 15 Intelligence saving throw or be [stunned](z_CLI/rules/conditions.md#Stunned) until this grapple ends.

***Extract Brain.*** *Melee Weapon Attack:* `+7` to hit, reach 5 ft., one [incapacitated](z_CLI/rules/conditions.md#Incapacitated) humanoid [grappled](z_CLI/rules/conditions.md#Grappled) by the ceremorph. *Hit:* 55 (`10d10`) piercing damage. If this damage reduces the target to 0 hit points, the ceremorph kills the target by extracting and devouring its brain.

***Laser Pistol.*** *Ranged Weapon Attack:* `+5` to hit, range 40/120 ft., one target. *Hit:* 12 (`3d6 + 2`) radiant damage.

***Mind Blast (Recharge 5-6).*** The ceremorph magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a DC 15 Intelligence saving throw or take 22 (`4d8 + 4`) psychic damage and be [stunned](z_CLI/rules/conditions.md#Stunned) for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock