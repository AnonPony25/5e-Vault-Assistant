---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
aliases:
- "Spy Master"
---
# Spy Master
*Source: Monster Manual (2024) p. 295*  

Spy masters have extensive experience in gathering secrets while leaving no evidence of their presence.

## Spies

*Infiltrators and Informants*

- **Habitat.** Any  
- **Treasure.** [Implements](z_CLI/tables/random-magic-items-implements.md), Individual  

Spies gather information and disseminate lies, manipulating people to gain the results the spies' patrons desire. They're trained to manipulate, infiltrate, and—when necessary—escape in a hurry. Many adopt disguises, aliases, or code names to maintain anonymity. Roll on or choose a result from the Spy Personas table to inspire a spy's disguise.

**Spy Personas**

| dice: 1d4 | The Spy Disguises Themself As... |
|-----------|----------------------------------|
| 1 | A bard or traveling performer. |
| 2 | A captive or servant of a monster or villain. |
| 3 | A dignitary or traveler from a distant land. |
| 4 | A visitor from a different time or world. |
^spy-personas

## Statblock

```ad-statblock
title: Spy Master
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Spy%20Master.webp#token)
*Small or Medium humanoid, Neutral*

- **Armor Class** 19
- **Hit Points** 137 (`25d8 + 25`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|20 (+5)|12 (+1)|18 (+4)|16 (+3)|16 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +9, Constitution +5, Intelligence +8, Wisdom +7
- **Skills** [Deception](z_CLI/rules/skills.md#Deception) +7, [Insight](z_CLI/rules/skills.md#Insight) +7, [Investigation](z_CLI/rules/skills.md#Investigation) +8, [Perception](z_CLI/rules/skills.md#Perception) +11, [Sleight of Hand](z_CLI/rules/skills.md#Sleight%20of%20Hand) +9, [Stealth](z_CLI/rules/skills.md#Stealth) +13
- **Senses** passive Perception 21
- **Gear** [hand crossbow](z_CLI/items/hand-crossbow-xphb.md), [rapier](z_CLI/items/rapier-xphb.md), [thieves' tools](z_CLI/items/thieves-tools-xphb.md)
- **Languages** Common plus two other languages
- **Challenge** 10

## Actions

***Multiattack.*** The spy makes three attacks, using Rapier or Hand Crossbow in any combination.

***Rapier.*** *Melee Attack Roll:* `+9`, reach 5 ft. *Hit:* 14 (`2d8 + 5`) Piercing damage plus 7 (`2d6`) Poison damage.

***Hand Crossbow.*** *Ranged Attack Roll:* `+9`, range 30/120 ft. *Hit:* 12 (`2d6 + 5`) Piercing damage plus 9 (`2d8`) Poison damage.

***Smoke Bomb (1/Day).*** The spy throws a bomb to a point it can see within 30 feet of itself. *Constitution Saving Throw:* DC 16, each creature in a 20-foot-radius [Sphere](z_CLI/rules/variant-rules/sphere-area-of-effect-xphb.md) centered on that point. *Failure:* 28 (`8d6`) Poison damage, and the target has the [Blinded](z_CLI/rules/conditions.md#Blinded) condition until the end of the spy's next turn. *Success:* Half damage only.

## Bonus Actions

***Cunning Action.*** The spy takes the [Dash](z_CLI/rules/actions.md#Dash), [Disengage](z_CLI/rules/actions.md#Disengage), or [Hide](z_CLI/rules/actions.md#Hide) action.
```
^statblock

## Environment

any