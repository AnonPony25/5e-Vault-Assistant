---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/kftgv
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/monstrosity
aliases:
- "Juvenile Eldritch Horror"
---
# Juvenile Eldritch Horror
*Source: Keys from the Golden Vault p. 24*  

```ad-statblock
title: Juvenile Eldritch Horror
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/KftGV/Juvenile%20Eldritch%20Horror.webp#token)
*Huge monstrosity, Neutral Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 168 (`16d12 + 64`)
- **Speed** 50 ft., climb 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|16 (+3)|18 (+4)|18 (+4)|14 (+2)|12 (+1)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** [Perception](z_CLI/rules/skills.md#Perception) +6, [Stealth](z_CLI/rules/skills.md#Stealth) +7
- **Senses** [darkvision](z_CLI/rules/senses.md#Darkvision) 90 ft., passive Perception 16
- **Damage Immunities** lightning
- **Languages** —
- **Challenge** 11

## Actions

***Multiattack.*** The eldritch horror makes two attacks: one with its bite and one to constrict.

***Bite.*** *Melee Weapon Attack:* `+10` to hit, reach 10 ft., one target. *Hit:* 22 (`3d10 + 6`) piercing damage.

***Constrict.*** *Melee Weapon Attack:* `+10` to hit, reach 5 ft., one Large or smaller creature. *Hit:* 17 (`2d10 + 6`) bludgeoning damage plus 17 (`2d10 + 6`) slashing damage. The target is [grappled](z_CLI/rules/conditions.md#Grappled) (escape DC 16) if the eldritch horror isn't already constricting a creature, and the target is [restrained](z_CLI/rules/conditions.md#Restrained) until this grapple ends.

***Lightning Breath (Recharge 5-6).*** The eldritch horror exhales a line of lightning that is 20 feet long and 5 feet wide. Each creature in that line must make a DC 16 Dexterity saving throw, taking 66 (`12d10`) lightning damage on a failed save, or half as much damage on a successful one.

***Swallow.*** The eldritch horror makes one bite attack against a Medium or smaller target it is grappling. If the attack hits, the target is also swallowed, and the grapple ends. While swallowed, the target is [blinded](z_CLI/rules/conditions.md#Blinded) and [restrained](z_CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the eldritch horror, and it takes 21 (`6d6`) acid damage at the start of each of the eldritch horror's turns. A eldritch horror can have only one creature swallowed at a time.

If the eldritch horror takes 30 damage or more on a single turn from the swallowed creature, the eldritch horror must succeed on a DC 14 Constitution saving throw at the end of that turn or regurgitate the creature, which falls [prone](z_CLI/rules/conditions.md#Prone) in a space within 10 feet of the eldritch horror. If the eldritch horror dies, a swallowed creature is no longer [restrained](z_CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 15 feet of movement, exiting [prone](z_CLI/rules/conditions.md#Prone).

***Spellcasting.*** The eldritch horror casts one of the following spells, requiring no components and using Intelligence as the spellcasting ability (save DC 14):

**2/day each:** [blindness/deafness](z_CLI/spells/blindness-deafness-xphb.md), [blur](z_CLI/spells/blur-xphb.md)

**1/day:** [project image](z_CLI/spells/project-image-xphb.md)
```
^statblock