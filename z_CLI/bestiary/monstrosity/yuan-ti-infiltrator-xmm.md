---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
aliases:
- "Yuan-ti Infiltrator"
---
# Yuan-ti Infiltrator
*Source: Monster Manual (2024) p. 342*  

Infiltrators can pass as human, their serpentine features limited to scaly skin, forked tongues, and other minor or internal transformations. These spies insinuate themselves among their rivals, manipulating others and making foes vulnerable to the plots of more powerful yuan-ti.

## Yuan-ti

*Power-Hungry Serpentine Conspirators*

- **Habitat.** Desert, Forest, Swamp, Urban  
- **Treasure.** [Relics](z_CLI/tables/random-magic-items-relics.md)  

Exploiting pacts with sinister supernatural forces, yuan-ti bargain away their humanity for the lethality and predatory deviousness of serpents. From hidden bastions, they manipulate rulers and the wealthy, seeking to control the world. Many yuan-ti possess venomous magic, which often manifests as fangs or striking serpents.

Yuan-ti have humanlike forms with a variety of horrifying serpentine transformations. Some have a scattering of reptilian scales, while others are giants that are more snake than human. Typically, the more snakelike yuan-ti are, the greater esteem they hold among their kind.

Yuan-ti might gain their reptilian features through dangerous supernatural rites. Roll on or choose a result from the Yuan-ti Transformations table to inspire how yuan-ti obtain their serpentine aspects.

**Yuan-ti Transformations**

| dice: 1d6 | A Yuan-ti Gained Its Snake Features From... |
|-----------|---------------------------------------------|
| 1 | Bargaining parts of its soul to a pantheon of serpentine demigods. |
| 2 | A curse laid on its people in the distant past. |
| 3 | The dream-venom of Merrshaulk, a slumbering snake god. |
| 4 | Experiments by spirit nagas or other yuan-ti. |
| 5 | A ritual involving the skin of a fiendish snake. |
| 6 | Trials to excise its "weak" human parts. |
^yuan-ti-transformations

> [!quote] A quote from Last Message of Sorril Venil, Explorer of the Labyrinth of Madness  
> 
> Great magic, twisted and corrupted... Malice beyond reckoning... Flesh reshaped, becoming serpentine horrors...


## Statblock

```ad-statblock
title: Yuan-ti Infiltrator
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Yuan-ti%20Infiltrator.webp#token)
*Medium monstrosity, Neutral Evil*

- **Armor Class** 11
- **Hit Points** 40 (`9d8`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|12 (+1)|11 (+0)|13 (+1)|14 (+2)|12 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** [Deception](z_CLI/rules/skills.md#Deception) +5, [Perception](z_CLI/rules/skills.md#Perception) +4, [Stealth](z_CLI/rules/skills.md#Stealth) +3
- **Senses** [Darkvision](z_CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 14
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](z_CLI/rules/conditions.md#Poisoned)
- **Gear** [scimitar](z_CLI/items/scimitar-xphb.md)
- **Languages** Abyssal, Common, Draconic
- **Challenge** 1

## Traits

***Magic Resistance.*** The yuan-ti has [Advantage](z_CLI/rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The yuan-ti makes two Scimitar attacks.

***Scimitar.*** *Melee Attack Roll:* `+3`, reach 5 ft. *Hit:* 4 (`1d6 + 1`) Slashing damage.

***Poison Ray.*** *Ranged Attack Roll:* `+4`, range 120 ft. *Hit:* 9 (`2d6 + 2`) Poison damage.

***Spellcasting.*** The yuan-ti casts one of the following spells, requiring no Material components and using Wisdom as the spellcasting ability (spell save DC 12):

**At will:** [Animal Friendship](z_CLI/spells/animal-friendship-xphb.md) (snakes only)

**2/day:** [Suggestion](z_CLI/spells/suggestion-xphb.md)
```
^statblock

## Environment

desert, forest, swamp, urban