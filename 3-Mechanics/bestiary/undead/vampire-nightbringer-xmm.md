---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/undead
aliases:
- "Vampire Nightbringer"
---
# Vampire Nightbringer
*Source: Monster Manual (2024) p. 316*  

Born of necromantic rituals and planes of existence suffused with negative energy, vampire nightbringers manipulate shadows and feed on the raw life force of living creatures.

## Vampires

*Blood-Sucking Lords of the Night*

- **Habitat.** Underdark, Urban  
- **Treasure.** Any  

Vampires disguise their accursed, immortal natures, passing as mortals to feed on the blood of the living. While the youngest vampires might be little more than bloodthirsty servants of their creators, the eldest possess incredible cunning and control over supernatural forces of the night.

Undead vampires lie dormant during the day, retreating to resting places hidden from foes and the sun's searing rays. Roll on or choose a result from the Vampire Resting Places table to inspire a vampire's grim sanctuary.

**Vampire Resting Places**

| dice: 1d6 | The Vampire's Resting Place Is... |
|-----------|-----------------------------------|
| 1 | Among the roots of a dead tree. |
| 2 | At the bottom of a stagnant pool. |
| 3 | A coffin filled with grave dirt. |
| 4 | A large pot full of blood or vinegar. |
| 5 | A space accessible only by shape-shifting. |
| 6 | Within a statue or suit of armor. |
^vampire-resting-places

### Vampire Lairs

Vampires and vampire umbral lords create sanctuaries apart from the living, whether hidden in cosmopolitan cities or sequestered in ruins where they dwelled in life.

> [!quote] A quote from Astarion, Vampire Spawn  
> 
> Darling, you are simply delicious...


## Statblock

```ad-statblock
title: Vampire Nightbringer
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Vampire%20Nightbringer.webp#token)
*Small or Medium undead, Neutral Evil*

- **Armor Class** 16
- **Hit Points** 142 (`19d8 + 57`)
- **Speed** 30 ft., fly 30 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|18 (+4)|16 (+3)|13 (+1)|14 (+2)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +7, Wisdom +5
- **Skills** [Perception](z_CLI/rules/skills.md#Perception) +5, [Stealth](z_CLI/rules/skills.md#Stealth) +7
- **Senses** [Darkvision](z_CLI/rules/senses.md#Darkvision) 120 ft., passive Perception 15
- **Damage Immunities** cold, necrotic
- **Condition Immunities** [charmed](z_CLI/rules/conditions.md#Charmed), [exhaustion](z_CLI/rules/conditions.md#Exhaustion), [frightened](z_CLI/rules/conditions.md#Frightened)
- **Languages** Common plus one other language
- **Challenge** 8

## Traits

***Sunlight Hypersensitivity.*** The vampire takes 10 Radiant damage if it starts its turn in sunlight. While in sunlight, it has [Disadvantage](z_CLI/rules/variant-rules/disadvantage-xphb.md) on attack rolls and ability checks.

## Actions

***Multiattack.*** The vampire makes one Bite attack and one Shadow Strike attack.

***Bite.*** *Melee Attack Roll:* `+7`, reach 5 ft. *Hit:* 7 (`1d6 + 4`) Piercing damage plus 10 (`3d6`) Necrotic damage. The target's [Hit Point](z_CLI/rules/variant-rules/hit-points-xphb.md) maximum decreases by an amount equal to the Necrotic damage taken, and the vampire regains [Hit Points](z_CLI/rules/variant-rules/hit-points-xphb.md) equal to that amount.

***Shadow Strike.*** *Melee Attack Roll:* `+7`, reach 5 ft. *Hit:* 7 (`1d6 + 4`) Slashing damage plus 14 (`4d6`) Cold damage.

## Bonus Actions

***Shadow Stealth.*** While in [Dim Light](z_CLI/rules/variant-rules/dim-light-xphb.md) or [Darkness](z_CLI/rules/variant-rules/darkness-xphb.md), the vampire takes the [Hide](z_CLI/rules/actions.md#Hide) action.
```
^statblock

## Environment

underdark, urban