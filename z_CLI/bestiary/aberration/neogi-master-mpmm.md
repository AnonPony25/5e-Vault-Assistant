---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration/warlock
aliases:
- "Neogi Master"
---
# Neogi Master
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 192*  

Neogi masters use magic, as a result of a pact between neogi and aberrant entities they met during their journey from their home world. These entities—known by such names as Acamar, Caiphon, Gibbeth, and Hadar—resemble stars and embody the essence of evil.

## Neogi

> [!quote] A quote from Mordenkainen  
> 
> Only the malevolent or the desperate do business with neogi. I generally advise against working with beings who view you as property or prey.

A neogi looks like an outsize spider with an eel's neck and head. It can poison the body and the mind of its targets and can subjugate even beings that are physically superior.

Neogi usually dwell in far-flung locations on the Material Plane, as well as in the Astral Plane and the Ethereal Plane. They left their home world long ago to conquer and devour creatures in other realms. During this era, they dominated umber hulks and used them to build sleek, spidery ships capable of traversing the multiverse.

## Statblock

```ad-statblock
title: Neogi Master
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Neogi%20Master.webp#token)
*Medium aberration (warlock), Typically  Lawful Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 71 (`11d8 + 22`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|16 (+3)|14 (+2)|16 (+3)|12 (+1)|18 (+4)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +3
- **Skills** [Arcana](z_CLI/rules/skills.md#Arcana) +5, [Deception](z_CLI/rules/skills.md#Deception) +6, [Intimidation](z_CLI/rules/skills.md#Intimidation) +6, [Perception](z_CLI/rules/skills.md#Perception) +3, [Persuasion](z_CLI/rules/skills.md#Persuasion) +6
- **Senses** [darkvision](z_CLI/rules/senses.md#Darkvision) 120 ft., passive Perception 13
- **Languages** Common, Deep Speech, Undercommon, telepathy 30 ft.
- **Challenge** 4

## Traits

***Devil's Sight.*** Magical darkness doesn't impede the neogi's [darkvision](z_CLI/rules/senses.md#Darkvision).

***Mental Fortitude.*** The neogi has advantage on saving throws against being [charmed](z_CLI/rules/conditions.md#Charmed) or [frightened](z_CLI/rules/conditions.md#Frightened), and magic can't put the neogi to sleep.

***Spider Climb.*** The neogi can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

## Actions

***Multiattack.*** The neogi makes one Bite attack and one Claw attack, or it makes two Tentacle of Hadar attacks.

***Bite.*** *Melee Weapon Attack:* `+5` to hit, reach 5 ft., one target. *Hit:* 6 (`1d6 + 3`) piercing damage plus 14 (`4d6`) poison damage, and the target must succeed on a DC 12 Constitution saving throw or become [poisoned](z_CLI/rules/conditions.md#Poisoned) for 1 minute. A target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Claw.*** *Melee Weapon Attack:* `+5` to hit, reach 5 ft., one target. *Hit:* 8 (`2d4 + 3`) piercing damage.

***Tentacle of Hadar.*** *Ranged Spell Attack:* `+6` to hit, range 120 ft., one target. *Hit:* 14 (`3d6 + 4`) necrotic damage, and the target can't take reactions until the end of the neogi's next turn, as a spectral tentacle clings to the target.

***Spellcasting.*** The neogi casts one of the following spells, using Charisma as the spellcasting ability (spell save DC 14):

**At will:** [guidance](z_CLI/spells/guidance-xphb.md), [mage hand](z_CLI/spells/mage-hand-xphb.md), [minor illusion](z_CLI/spells/minor-illusion-xphb.md), [prestidigitation](z_CLI/spells/prestidigitation-xphb.md)

**1/day each:** [dimension door](z_CLI/spells/dimension-door-xphb.md), [hold person](z_CLI/spells/hold-person-xphb.md), [hunger of Hadar](z_CLI/spells/hunger-of-hadar-xphb.md)

## Bonus Actions

***Enslave (Recharges after a Short or Long Rest).*** The neogi targets one creature it can see within 30 feet of it. The target must succeed on a DC 14 Wisdom saving throw or be magically [charmed](z_CLI/rules/conditions.md#Charmed) by the neogi for 1 day, or until the neogi dies or is more than 1 mile from the target. The [charmed](z_CLI/rules/conditions.md#Charmed) target obeys the neogi's commands and can't take reactions, and the neogi and the target can communicate telepathically with each other at a distance of up to 1 mile. Whenever the [charmed](z_CLI/rules/conditions.md#Charmed) target takes damage, it can repeat the saving throw, ending the effect on itself on a success.
```
^statblock

## Environment

hill, underdark