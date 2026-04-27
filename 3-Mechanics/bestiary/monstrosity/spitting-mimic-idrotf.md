---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/idrotf
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity/shapechanger
aliases:
- "Spitting Mimic"
---
# Spitting Mimic
*Source: Icewind Dale: Rime of the Frostmaiden p. 302*  

Mimics are shape-shifting monsters described in the *Monster Manual*. The variant presented here is a particularly large and voracious specimen—the result of Netherese experiments on ordinary mimics—that spits acid.

```ad-statblock
title: Spitting Mimic
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Spitting%20Mimic.webp#token)
*Large monstrosity (shapechanger), Neutral*

- **Armor Class** 14 (natural armor)
- **Hit Points** 85 (`10d10 + 30`)
- **Speed** 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)|12 (+1)|17 (+3)| 9 (-1)|15 (+2)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** [Stealth](z_CLI/rules/skills.md#Stealth) +7
- **Senses** [darkvision](z_CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 12
- **Damage Immunities** acid
- **Condition Immunities** [prone](z_CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 5

## Traits

***Shapechanger.*** The mimic can use its action to polymorph into an object or back into its true, amorphous form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.

***Adhesive (Object Form Only).*** The mimic adheres to anything that touches it. A Huge or smaller creature adhered to the mimic is also [grappled](z_CLI/rules/conditions.md#Grappled) by it (escape DC 16). Ability checks made to escape this grapple have disadvantage.

***False Appearance (Object Form Only).*** While the mimic remains motionless, it is indistinguishable from an ordinary object.

***Grappler.*** The mimic has advantage on attack rolls against any creature [grappled](z_CLI/rules/conditions.md#Grappled) by it.

***Magic Resistance.*** The mimic has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The mimic attacks three times: twice with its pseudopods and once with its bite.

***Pseudopods.*** *Melee Weapon Attack:* `+8` to hit, reach 10 ft., one target. *Hit:* 10 (`1d10 + 5`) bludgeoning damage. If the mimic is in object form, the target is subjected to its Adhesive trait.

***Bite.*** *Melee Weapon Attack:* `+8` to hit, reach 5 ft., one creature. *Hit:* 10 (`1d10 + 5`) piercing damage plus 7 (`2d6`) acid damage.

***Spit Acid (Recharge 5-6).*** The mimic spits acid at one creature it can see within 30 feet of it. The target must make a DC 14 Dexterity saving throw, taking 32 (`9d6 + 1`) acid damage on failed save, or half as much damage on a successful one.
```
^statblock