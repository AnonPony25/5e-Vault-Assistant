---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/cos
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
aliases:
- "Guardian Portrait"
---
# Guardian Portrait
*Source: Curse of Strahd p. 227*  

A guardian portrait looks like a finely rendered and beautifully framed work of art, usually depicting someone important in a realistic manner. The picture and its frame are bound with powerful magic and are inseparable.

## Living Image

The eyes of the figure depicted in the painting are imbued with [darkvision](z_CLI/rules/senses.md#Darkvision), and they appear to follow creatures that move in front of them.

## Innate Spells

When a guardian portrait attacks, the figure in the painting animates and moves as though alive (albeit in two dimensions). The guardian portrait has no effective melee attacks, but it has a repertoire of innate spells that it can cast. When it casts a spell, the figure painted on the canvas makes all the appropriate somatic gestures and verbal incantations for the spell.

## Statblock

```ad-statblock
title: Guardian Portrait
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoS/Guardian%20Portrait.webp#token)
*Medium construct, Unaligned*

- **Armor Class** 5 (natural armor)
- **Hit Points** 22 (`5d8`)
- **Speed** 0 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 (-5)| 1 (-5)|10 (+0)|14 (+2)|10 (+0)|10 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** [darkvision](z_CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 10
- **Damage Immunities** poison
- **Condition Immunities** [charmed](z_CLI/rules/conditions.md#Charmed), [exhaustion](z_CLI/rules/conditions.md#Exhaustion), [frightened](z_CLI/rules/conditions.md#Frightened), [grappled](z_CLI/rules/conditions.md#Grappled), [paralyzed](z_CLI/rules/conditions.md#Paralyzed), [petrified](z_CLI/rules/conditions.md#Petrified), [poisoned](z_CLI/rules/conditions.md#Poisoned), [prone](z_CLI/rules/conditions.md#Prone), [restrained](z_CLI/rules/conditions.md#Restrained)
- **Languages** Common, plus up to two other languages
- **Challenge** 1

## Traits

***Innate Spellcasting.*** The portrait's innate spellcasting ability is Intelligence (spell save DC 12). The portrait can innately cast the following spells, requiring no material components:

**3/day each:** [counterspell](z_CLI/spells/counterspell-xphb.md), [crown of madness](z_CLI/spells/crown-of-madness-xphb.md), [hypnotic pattern](z_CLI/spells/hypnotic-pattern-xphb.md), [telekinesis](z_CLI/spells/telekinesis-xphb.md)

***Constructed Nature.*** An animated object doesn't require air, food, drink, or sleep.

The magic that animates an object is dispelled when the construct drops to 0 hit points. An animated object reduced to 0 hit points becomes inanimate and is too damaged to be of much use or value to anyone.

***Antimagic Susceptibility.*** The portrait is [incapacitated](z_CLI/rules/conditions.md#Incapacitated) while in the area of an [antimagic field](z_CLI/spells/antimagic-field-xphb.md). If targeted by [dispel magic](z_CLI/spells/dispel-magic-xphb.md), the portrait must succeed on a Constitution saving throw against the caster's spell save DC or become [unconscious](z_CLI/rules/conditions.md#Unconscious) for 1 minute.

***False Appearance.*** While the figure in the portrait remains motionless, the portrait is indistinguishable from a normal painting.
```
^statblock