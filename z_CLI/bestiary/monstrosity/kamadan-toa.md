---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/toa
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
aliases:
- "Kamadan"
---
# Kamadan
*Source: Tomb of Annihilation p. 225*  

A kamadan (pronounced KAM-ah-dan) is a feline predator that resembles a leopard with six snakes sprouting from its shoulders. Although it bears a passing resemblance to a displacer beast, the two creatures are unrelated (though some sages claim otherwise).

Kamadans typically hunt alone or in mated pairs. They can exhale clouds of sleep gas, which they typically do before entering melee combat. If a kamadan has both conscious and unconscious enemies within striking range, it tries to kill the conscious enemies first before finishing off any sleeping foes.

```ad-statblock
title: Kamadan
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Kamadan.webp#token)
*Large monstrosity, Unaligned*

- **Armor Class** 13 (natural armor)
- **Hit Points** 67 (`9d10 + 18`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|16 (+3)|14 (+2)| 3 (-4)|14 (+2)|10 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** [Perception](z_CLI/rules/skills.md#Perception) +4, [Stealth](z_CLI/rules/skills.md#Stealth) +7
- **Senses** passive Perception 14
- **Languages** —
- **Challenge** 4

## Traits

***Keen Smell.*** The kamadan has advantage on Wisdom ([Perception](z_CLI/rules/skills.md#Perception)) checks that rely on smell.

***Pounce.*** If the kamadan moves at least 20 feet straight toward a creature and then hits it with a claw attack on the same turn that target must succeed on a DC 13 Strength saving throw or be knocked [prone](z_CLI/rules/conditions.md#Prone). If the target is knocked [prone](z_CLI/rules/conditions.md#Prone), the kamadan can make two attacks—one with its bite and one with its snakes—against it as a bonus action.

## Actions

***Multiattack.*** The kamadan makes two attacks: one with its bite or claw and one with its snakes.

***Bite.*** *Melee Weapon Attack:* `+5` to hit, reach 5 ft., one target. *Hit:* 6 (`1d6 + 3`) piercing damage.

***Claw.*** *Melee Weapon Attack:* `+5` to hit, reach 5 ft., one target. *Hit:* 6 (`1d6 + 3`) slashing damage.

***Snakes.*** *Melee Weapon Attack:* `+5` to hit, reach 5 ft., one creature. *Hit:* 6 (`1d6 + 3`) piercing damage, and the target must make a DC 12 Constitution saving throw, taking 21 (`6d6`) poison damage on a failed save, or half as much damage on a successful one.

***Sleep Breath (Recharges after a Short or Long Rest).*** The kamadan exhales sleep gas in a 30-foot cone. Each creature in that area must succeed on a DC 12 Constitution saving throw or fall [unconscious](z_CLI/rules/conditions.md#Unconscious) for 10 minutes. This effect ends for a creature if it takes damage or someone uses an action to wake it.
```
^statblock