---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/kftgv
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
aliases:
- "King Jhaeros"
---
# King Jhaeros
*Source: Keys from the Golden Vault p. 158*  

Known for its exquisite glasswork, Ghalasine was a prosperous city ruled by King Jhaeros Astolko. Governing from Castle Cinis, Jhaeros was advised by two councilors, Regine LaVerne and Charmayne Daymore, and a guard captain named Naevys Tharesso. Jhaeros's rule was compassionate, just, and kind. Over the last year, however, Naevys watched with growing concern as Jhaeros became more withdrawn and secretive, closing Ghalasine to trade and failing to honor his alliances.

Jhaeros has been transformed into a heartless puppet under Charmayne's command.

```ad-statblock
title: King Jhaeros
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/KftGV/King%20Jhaeros.webp#token)
*Large construct, Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 133 (`14d10 + 56`)
- **Speed** 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)| 9 (-1)|18 (+4)|10 (+0)|10 (+0)|10 (+0)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** [darkvision](z_CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 9
- **Damage Immunities** poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
- **Condition Immunities** [charmed](z_CLI/rules/conditions.md#Charmed), [exhaustion](z_CLI/rules/conditions.md#Exhaustion), [frightened](z_CLI/rules/conditions.md#Frightened), [paralyzed](z_CLI/rules/conditions.md#Paralyzed), [petrified](z_CLI/rules/conditions.md#Petrified), [poisoned](z_CLI/rules/conditions.md#Poisoned)
- **Languages** understands Common, Draconic, Elvish, and Ignan but can't speak
- **Challenge** 9

## Traits

***Fire Absorption.*** Whenever Jhaeros is subjected to fire damage, he takes no damage and instead regains a number of hit points equal to the fire damage dealt.

***Berserk.*** Whenever Jhaeros starts its turn with 60 hit points or fewer, roll a `d6`. On a 6, Jhaeros goes berserk. On each of its turns while berserk, Jhaeros attacks the nearest creature it can see. If no creature is near enough to move to and attack, Jhaeros attacks an object, with preference for an object smaller than itself. Once Jhaeros goes berserk, it continues to do so until it is destroyed or regains all its hit points.

***Immutable Form.*** Jhaeros is immune to any spell or effect that would alter its form.

***Magic Resistance.*** Jhaeros has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** Jhaeros's weapon attacks are magical.

***Ashen Creature.*** When Jhaeros drops to 0 hit points, he explodes in a harmless cloud of ashes, leaving nothing else behind.

## Actions

***Multiattack.*** Jhaeros makes two slam attacks.

***Slam.*** *Melee Weapon Attack:* `+8` to hit, reach 5 ft., one target. *Hit:* 16 (`2d10 + 5`) bludgeoning damage. If the target is a creature, it must succeed on a DC 15 Constitution saving throw or have its hit point maximum reduced by an amount equal to the damage taken. The target dies if this attack reduces its hit point maximum to 0. The reduction lasts until removed by the  [greater restoration](z_CLI/spells/greater-restoration-xphb.md) spell or other magic.

***Haste (Recharge 5-6).*** Until the end of its next turn, Jhaeros magically gains a +2 bonus to its AC, has advantage on Dexterity saving throws, and can use its slam attack as a bonus action.
```
^statblock