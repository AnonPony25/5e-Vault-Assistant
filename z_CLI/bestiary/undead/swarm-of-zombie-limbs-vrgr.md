---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/vrgr
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
aliases:
- "Swarm of Zombie Limbs"
---
# Swarm of Zombie Limbs
*Source: Van Richten's Guide to Ravenloft p. 254*  

Among the undead, a lone zombie ranks far from the most menacing. The horror of the shambling dead lies not in their individual menace, though, but their numbers, their persistence, and their disregard for their own well-being. A throng of zombies will douse a forest fire with their own ashes or march into a dragon's maw until the monster chokes. In the course of their relentless marches, zombies might suffer all manner of trauma, potentially reducing them to masses of crawling limbs, infecting them with terrible diseases (see zombie plague spreader), or crushing an entire horde into a single, rotting titan (see zombie clot).

## Zombie Apocalypses

Among the types of horror adventures detailed in "chapter 2", tales of uncontrolled zombie outbreaks orbit the "dark fantasy" and "disaster horror" genres. The horror of these adventures focuses not on the terror of a single zombie, but of countless individual threats overwhelming society. When creating your own undead calamities, consider the plots presented on the Zombie Apocalypses table.

**Zombie Apocalypses**

| dice: d4 | Zombie Plot |
|----------|-------------|
| 1 | A twisted wish causes those affected by healing magic and [potions of healing](z_CLI/items/potion-of-healing-xdmg.md) to rise as zombies. |
| 2 | Overwhelming magic reanimates zombies again and again as [swarms of zombie limbs](z_CLI/bestiary/undead/swarm-of-zombie-limbs-vrgr.md). |
| 3 | The githyanki unleash [zombie plague spreaders](z_CLI/bestiary/undead/zombie-plague-spreader-vrgr.md) to scour mind flayers from a world. |
| 4 | The seals containing an underground zombie horde fail, releasing ancient [zombie clots](z_CLI/bestiary/undead/zombie-clot-vrgr.md). |
^zombie-apocalypses

## Statblock

```ad-statblock
title: Swarm of Zombie Limbs
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VRGR/Swarm%20of%20Zombie%20Limbs.webp#token)
*Medium undead, Unaligned*

- **Armor Class** 10
- **Hit Points** 22 (`5d8`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|10 (+0)|10 (+0)| 3 (-4)| 8 (-1)| 5 (-3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** [blindsight](z_CLI/rules/senses.md#Blindsight) 30 ft. (blind beyond this radius), passive Perception 9
- **Damage Resistances** bludgeoning, piercing, slashing
- **Damage Immunities** poison
- **Condition Immunities** [charmed](z_CLI/rules/conditions.md#Charmed), [exhaustion](z_CLI/rules/conditions.md#Exhaustion), [frightened](z_CLI/rules/conditions.md#Frightened), [grappled](z_CLI/rules/conditions.md#Grappled), [paralyzed](z_CLI/rules/conditions.md#Paralyzed), [petrified](z_CLI/rules/conditions.md#Petrified), [poisoned](z_CLI/rules/conditions.md#Poisoned), [prone](z_CLI/rules/conditions.md#Prone), [restrained](z_CLI/rules/conditions.md#Restrained), [stunned](z_CLI/rules/conditions.md#Stunned)
- **Languages** —
- **Challenge** 1

## Traits

***Swarm.*** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny limb. The swarm can't regain hit points or gain temporary hit points.

***Unusual Nature.*** The swarm doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The swarm makes one Undead Mass attack and one Grasping Limbs attack.

***Undead Mass.*** *Melee Weapon Attack:* `+4` to hit, reach 0 ft., one target in the swarm's space. *Hit:* 5 (`1d6 + 2`) bludgeoning damage, or 4 (`1d4 + 2`) bludgeoning damage if the swarm has half of its hit points or fewer.

***Grasping Limbs.*** *Melee Weapon Attack:* `+4` to hit, reach 0 ft., one creature in the swarm's space. *Hit:* 7 (`2d6`) necrotic damage, and the creature must succeed on a DC 12 Strength saving throw or be [restrained](z_CLI/rules/conditions.md#Restrained). The creature can repeat the saving throw at the end of each of its turns, taking 7 (`2d6`) necrotic damage on a failed save. The creature is freed if it succeeds on this saving throw, the swarm moves out of the creature's space, or the swarm dies.
```
^statblock