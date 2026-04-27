---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
aliases:
- "Gnoll Demoniac"
---
# Gnoll Demoniac
*Source: Monster Manual (2024) p. 141*  

Gnoll demoniacs are berserkers that arise from gnolls who've ritualistically fed on flesh corrupted by the Abyss. Now embodying the ruinous hunger of Yeenoghu, these gnolls throw themselves into battle, heedless of odds or their own survival. Rampaging demoniacs even devour other gnolls in their wild frenzies.

## Gnolls

*Fiends in Feral Flesh*

- **Habitat.** Desert, Forest, Grassland, Hill  
- **Treasure.** [Armaments](z_CLI/tables/random-magic-items-armaments.md), Individual  

The first gnolls arose from hyenas that fed on flesh tainted by the Abyss. Their corruption and violence delighted the demon lord Yeenoghu, who encouraged their numbers and spread them across the multiverse. Ever since, gnolls have been the cackling servants of Yeenoghu, existing to cause ruin and to feast on what remains.

> [!quote] A quote from Iggwilv  
> 
> Yeenoghu claims gnolls not as his brood but as maggots purposefully released to infest a despised carcass. They are a pernicious rot the Beast of Butchery spreads across mortal worlds. Whatever they once were, they were remade and are now his.


## Statblock

```ad-statblock
title: Gnoll Demoniac
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Gnoll%20Demoniac.webp#token)
*Medium fiend, Chaotic Evil*

- **Armor Class** 16
- **Hit Points** 135 (`18d8 + 54`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|12 (+1)|17 (+3)|14 (+2)|15 (+2)|17 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +6, Constitution +6, Wisdom +5, Charisma +6
- **Skills** [Perception](z_CLI/rules/skills.md#Perception) +5
- **Senses** [Darkvision](z_CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 15
- **Languages** Abyssal, Common, Gnoll
- **Challenge** 8

## Actions

***Multiattack.*** The gnoll makes two Abyssal Strike attacks.

***Abyssal Strike.*** *Melee  or Ranged Attack Roll:* `+6`, reach 5 ft. or range 60 ft. *Hit:* 20 (`5d6 + 3`) Poison damage.

***Hunger of Yeenoghu (Recharge 5-6).*** The gnoll conjures a 30-foot [Cube](z_CLI/rules/variant-rules/cube-area-of-effect-xphb.md) of magical [Darkness](z_CLI/rules/variant-rules/darkness-xphb.md) originating from a point it can see within 60 feet, which lasts for 1 minute or until the gnoll's [Concentration](z_CLI/rules/conditions.md#Concentration) ends on it. This area is [Difficult Terrain](z_CLI/rules/variant-rules/difficult-terrain-xphb.md). *Dexterity Saving Throw:* DC 14, any creature that starts its turn in this area or enters it for the first time on a turn. *Failure:* 28 (`8d6`) Necrotic damage, and the gnoll or a creature of its choice it can see gains 10 [Temporary Hit Points](z_CLI/rules/variant-rules/temporary-hit-points-xphb.md). *Success:* Half damage only.

## Bonus Actions

***Rampage (2/Day).*** Immediately after dealing damage to a creature that is already [Bloodied](z_CLI/rules/conditions.md#Bloodied), the gnoll moves up to half its [Speed](z_CLI/rules/variant-rules/speed-xphb.md), and it makes one Abyssal Strike attack.
```
^statblock

## Environment

desert, forest, grassland, hill