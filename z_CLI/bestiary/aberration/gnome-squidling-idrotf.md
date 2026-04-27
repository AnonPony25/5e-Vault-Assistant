---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/idrotf
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/aberration
aliases:
- "Gnome Squidling"
---
# Gnome Squidling
*Source: Icewind Dale: Rime of the Frostmaiden p. 303*  

Mind flayers, which are described in the Monster Manual, are created through ceremorphosis, a process that begins with the implantation of an illithid tadpole in the brain of a humanoid host. After about seven days in its new home, the tadpole transforms its host into a mind flayer. The new creation typically retains no memory of its previous existence.

When the process of turning a gnome into a mind flayer goes horribly awry, the result is a gnome squidling—a deformed mind flayer with weak, spindly limbs and oversized tentacles. It relies on levitation to keep its body aloft and uses its tentacles like legs, to propel it along whatever surface it's floating above. Most mind flayers destroy squidlings on sight, so it's rare to see one or more of these creatures.

Squidlings eat brains for sustenance, just like other mind flayers do, and they don't care where the brains come from.

```ad-statblock
title: Gnome Squidling
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Gnome%20Squidling.webp#token)
*Small aberration, Unaligned*

- **Armor Class** 8
- **Hit Points** 10 (`3d6`)
- **Speed** 15 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 4 (-3)| 7 (-2)|10 (+0)| 4 (-3)|10 (+0)| 3 (-4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** [darkvision](z_CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 10
- **Languages** understands Deep Speech and Gnomish but can't speak, telepathy 60 ft.
- **Challenge** 1/2

## Traits

***Innate Spellcasting (Psionics).*** The squidling's innate spellcasting ability is Intelligence (spell save DC 7). It can innately cast [levitate](z_CLI/spells/levitate-xphb.md) at will, requiring no components.


***Magic Resistance.*** The squidling has advantage on saving throws against spells and other magical effects.

## Actions

***Tentacles.*** *Melee Weapon Attack:* `+0` to hit, reach 5 ft., one creature. *Hit:* 5 (`2d4`) psychic damage. If the target is Medium or smaller, it is [grappled](z_CLI/rules/conditions.md#Grappled) (escape DC 7) and must succeed on a DC 7 Intelligence saving throw or be [stunned](z_CLI/rules/conditions.md#Stunned) until this grapple ends.

***Extract Brain.*** *Melee Weapon Attack:* `+0` to hit, reach 5 ft., one [incapacitated](z_CLI/rules/conditions.md#Incapacitated) creature [grappled](z_CLI/rules/conditions.md#Grappled) by the squidling. *Hit:* 27 (`5d10`) piercing damage. If this damage reduces the target to 0 hit points, the squidling kills the target by extracting and devouring its brain.

***Mind Tickle (Recharge 5-6).*** The squidling magically emits psychic energy in a 30-foot cone. Each creature in that area must succeed on a DC 7 Intelligence saving throw or take 2 (`1d4`) psychic damage and be [stunned](z_CLI/rules/conditions.md#Stunned) until the end of its next turn.
```
^statblock