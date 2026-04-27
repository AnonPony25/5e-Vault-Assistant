---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/cos
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/construct
aliases:
- "Baba Lysaga's Creeping Hut"
---
# Baba Lysaga's Creeping Hut
*Source: Curse of Strahd p. 226*  

Baba Lysaga built a hut atop the rotting stump of a giant tree that was felled long ago. It was only after she embedded a magic gemstone in the hut that the whole thing was imbued with a semblance of life. When she wills it to do so, the hut pulls its gigantic roots free of the earth and shambles around like a spidery behemoth, shaking the ground with every step. The hut attacks with its flailing and stomping roots. It can also use its roots to fling large rocks.

## Hut Interior

The hut is a 15-foot-square, ramshackle wooden building with a gently sloping thatch roof. Its furnishings have been bolted to the floor, since the hut lurches from side to side when it walks.

## Heart of the Hut

The gemstone that has given life to Baba Lysaga's hut was previously buried in the Wizard of Wines vineyard. The gem was one of three imbued with life-giving magic that made the grapevines in the vineyard healthier, guaranteeing the finest wines. Baba Lysaga stole one of the gems and perverted its magic, using it instead to animate her wooden hut.

Removing the gem from the hut renders the hut [incapacitated](z_CLI/rules/conditions.md#Incapacitated). That task is easier said than done, however. The glowing green gem is contained in a cavity in the stump, beneath the rotted floorboards of the hut. The floorboards can be ripped up with a successful DC 14 Strength check or smashed by dealing 10 damage to them. Once the floorboards are out of the way, a creature can reach into the cavity and snatch the gem. But if someone attempts this while the hut is alive, the cavity sprouts wooden teeth, becoming a mouth that bites anything that tries to remove the gem; a creature trying to remove the gem must make a DC 20 Dexterity saving throw. On a successful save, the creature claims the stone without getting bitten. On a failed save, the creature is bitten for 10 (`3d6`) piercing damage and fails to obtain the gem.

## Statblock

```ad-statblock
title: Baba Lysaga's Creeping Hut
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoS/Baba%20Lysaga%27s%20Creeping%20Hut.webp#token)
*Gargantuan construct, Unaligned*

- **Armor Class** 16 (natural armor)
- **Hit Points** 263 (`17d20 + 85`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|26 (+8)| 7 (-2)|20 (+5)| 1 (-5)| 3 (-4)| 3 (-4)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +9, Wisdom +0, Charisma +0
- **Skills** ⏤
- **Senses** [blindsight](z_CLI/rules/senses.md#Blindsight) 120 ft. (blind beyond this radius), passive Perception 6
- **Damage Immunities** poison, psychic
- **Condition Immunities** [blinded](z_CLI/rules/conditions.md#Blinded), [charmed](z_CLI/rules/conditions.md#Charmed), [deafened](z_CLI/rules/conditions.md#Deafened), [exhaustion](z_CLI/rules/conditions.md#Exhaustion), [frightened](z_CLI/rules/conditions.md#Frightened), [paralyzed](z_CLI/rules/conditions.md#Paralyzed), [petrified](z_CLI/rules/conditions.md#Petrified), [prone](z_CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 11

## Traits

***Constructed Nature.*** An animated object doesn't require air, food, drink, or sleep.

The magic that animates an object is dispelled when the construct drops to 0 hit points. An animated object reduced to 0 hit points becomes inanimate and is too damaged to be of much use or value to anyone.

***Antimagic Susceptibility.*** The hut is [incapacitated](z_CLI/rules/conditions.md#Incapacitated) while the magic gem that animates it is in the area of an [antimagic field](z_CLI/spells/antimagic-field-xphb.md). If targeted by [dispel magic](z_CLI/spells/dispel-magic-xphb.md), the hut must succeed on a Constitution saving throw against the caster's spell save DC or fall [unconscious](z_CLI/rules/conditions.md#Unconscious) for 1 minute.

***Siege Monster.*** The hut deals double damage to objects and structures.

## Actions

***Multiattack.*** The hut makes three attacks with its roots. It can replace one of these attacks with a rock attack.

***Root.*** *Melee Weapon Attack:* `+12` to hit, reach 60 ft., one target. *Hit:* 30 (`4d10 + 8`) bludgeoning damage.

***Rock.*** *Ranged Weapon Attack:* `+12` to hit, range 120 ft., one target. *Hit:* 21 (`3d8 + 8`) bludgeoning damage.
```
^statblock