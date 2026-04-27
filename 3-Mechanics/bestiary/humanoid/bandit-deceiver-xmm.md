---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
aliases:
- "Bandit Deceiver"
---
# Bandit Deceiver
*Source: Monster Manual (2024) p. 28*  

Bandit deceivers use magic to disguise their activities or create flashy distractions.

## Bandits

*Criminals and Scoundrels*

- **Habitat.** Any  
- **Treasure.** Any  

Bandits use the threat of violence to take what they want. Such criminals include gang members, desperadoes, and lawless mercenaries. Yet not all bandits are motivated by greed. Some are driven to lives of crime by unjust laws, desperation, or the threats of merciless leaders.

Roll on or choose a result from the Bandit Motivations table to determine the circumstances behind a bandit's crimes.

> [!quote] A quote from Jarlaxle  
> 
> I am he who rules the world, don't you know? One little piece at a time.

**Bandit Motivations**

| dice: 1d6 | The Bandit... |
|-----------|---------------|
| 1 | Fights only oppressors. |
| 2 | Is an ex-soldier who was discarded by their nation and now takes what they were promised. |
| 3 | Is in a gang that views nonmembers as foes. |
| 4 | Hesitantly serves a villainous leader. |
| 5 | Secretly works for a government or a regional ruler to sow chaos. |
| 6 | Takes what they need to survive. |
^bandit-motivations

## Statblock

```ad-statblock
title: Bandit Deceiver
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Bandit%20Deceiver.webp#token)
*Small or Medium humanoid, Neutral*

- **Armor Class** 16
- **Hit Points** 130 (`20d8 + 40`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 8 (-1)|16 (+3)|14 (+2)|17 (+3)|12 (+1)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +6, Intelligence +6
- **Skills** [Acrobatics](z_CLI/rules/skills.md#Acrobatics) +6, [Perception](z_CLI/rules/skills.md#Perception) +4, [Stealth](z_CLI/rules/skills.md#Stealth) +9
- **Senses** passive Perception 14
- **Gear** six [daggers](z_CLI/items/dagger-xphb.md), [wand](z_CLI/items/wand-xphb.md)
- **Languages** Common, Thieves' cant
- **Challenge** 7

## Actions

***Multiattack.*** The bandit makes three Dagger attacks.

***Dagger.*** *Melee  or Ranged Attack Roll:* `+6`, reach 5 ft. or range 20/60 ft. *Hit:* 8 (`2d4 + 3`) Piercing damage plus 10 (`3d6`) Poison damage.

***Blinding Flash (Recharge 4-6).*** *Constitution Saving Throw:* DC 14, each creature in a 10-foot-radius [Sphere](z_CLI/rules/variant-rules/sphere-area-of-effect-xphb.md) centered on a point the bandit can see within 120 feet. *Failure:* 13 (`3d6 + 3`) Radiant damage, and the target has the [Blinded](z_CLI/rules/conditions.md#Blinded) condition until the start of the bandit's next turn. *Success:* Half damage only.

***Spellcasting.*** The bandit casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 14):

**At will:** [Disguise Self](z_CLI/spells/disguise-self-xphb.md), [Mage Hand](z_CLI/spells/mage-hand-xphb.md), [Minor Illusion](z_CLI/spells/minor-illusion-xphb.md)

**1/day each:** [Hold Person](z_CLI/spells/hold-person-xphb.md) (level 4 version), [Mage Armor](z_CLI/spells/mage-armor-xphb.md) (included in AC), [Major Image](z_CLI/spells/major-image-xphb.md)
```
^statblock

## Environment

any