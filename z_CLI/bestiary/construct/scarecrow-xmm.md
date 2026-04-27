---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
aliases:
- "Scarecrow"
---
# Scarecrow
*Source: Monster Manual (2024) p. 269*  

## Scarecrow

*Servant of Superstition*

- **Habitat.** Grassland  
- **Treasure.** None  

Spirits of vengeance bound to crude frames, scarecrows arise from folk magic, the prayers of desperate commoners, or possession by spirits that died with violent work left undone. Scarecrows might serve those who created them or might defend a place, family, or community from threats—whether physical or to their way of life.

Although scarecrows take their name from rural effigies, they might take varied patchwork forms. Roll on or choose a result from the Scarecrow Frames table to inspire a scarecrow's appearance.

**Scarecrow Frames**

| dice: 1d8 | The Scarecrow Is Made From... |
|-----------|-------------------------------|
| 1 | Animal furs, bones, horns, and claws. |
| 2 | Beehives or wasp nests over a wicker frame. |
| 3 | A carved pumpkin atop a body of thick vines. |
| 4 | Nets, flotsam, grapnels, and fishing tackle. |
| 5 | Oversize stuffed animal or mannequin parts. |
| 6 | Rusty armor and torture devices. |
| 7 | A sackcloth head atop straw-stuffed clothes. |
| 8 | Wedding clothes that were never worn. |
^scarecrow-frames

```ad-statblock
title: Scarecrow
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Scarecrow.webp#token)
*Medium construct, Chaotic Evil*

- **Armor Class** 11
- **Hit Points** 27 (`6d8`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|13 (+1)|11 (+0)|10 (+0)|10 (+0)|13 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** [Darkvision](z_CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 10
- **Damage Vulnerabilities** fire
- **Damage Immunities** poison
- **Condition Immunities** [charmed](z_CLI/rules/conditions.md#Charmed), [exhaustion](z_CLI/rules/conditions.md#Exhaustion), [frightened](z_CLI/rules/conditions.md#Frightened), [paralyzed](z_CLI/rules/conditions.md#Paralyzed), [petrified](z_CLI/rules/conditions.md#Petrified), [poisoned](z_CLI/rules/conditions.md#Poisoned), [unconscious](z_CLI/rules/conditions.md#Unconscious)
- **Languages** Common plus one other language
- **Challenge** 1

## Actions

***Fearsome Claw.*** *Melee Attack Roll:* `+3`, reach 5 ft. *Hit:* 6 (`2d4 + 1`) Slashing damage, and the target has the [Frightened](z_CLI/rules/conditions.md#Frightened) condition until the end of the scarecrow's next turn.

***Terrifying Glare.*** *Wisdom Saving Throw:* DC 11, one creature the scarecrow can see within 30 feet. *Failure:* The target has the [Frightened](z_CLI/rules/conditions.md#Frightened) condition until the end of the scarecrow's next turn. While [Frightened](z_CLI/rules/conditions.md#Frightened), the target has the [Paralyzed](z_CLI/rules/conditions.md#Paralyzed) condition.
```
^statblock

## Environment

grassland