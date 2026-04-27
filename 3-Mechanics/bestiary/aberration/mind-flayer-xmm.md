---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration
aliases:
- "Mind Flayer"
---
# Mind Flayer
*Source: Monster Manual (2024) p. 214*  

A mind flayer's hunger for brains is outmeasured only by its thirst for dominance, and it embraces any plot that allows it to indulge both.

## Mind Flayers

*Brain-Eating Underdark Tyrants*

- **Habitat.** Underdark  
- **Treasure.** [Arcana](z_CLI/tables/random-magic-items-arcana.md)  

Scattered survivors of a world-ruining, multiversal empire, mind flayers lurk in secret conclaves hidden deep within Material Plane worlds. Within their alien sanctuaries, these wicked masterminds—also known as illithids—reshape the Underdark and its inhabitants to serve their unfathomable whims. Mind flayers are feared for their psionic powers, which allow them to stun and control other creatures, and for their horrific method of feeding: using their four slimy tentacles to extract the brains of their victims.

Mind flayers are infamous plotters and manipulators, concocting plans that reach beyond their subterranean realms. Aside from using their psionic powers to control others, mind flayers often experiment with their own bizarre life cycles, implanting other creatures with illithid young to create unnatural servants. Creatures such as grimlocks and intellect devourers result from mind flayers' biological tampering, while other Underdark-dwelling monsters—including kuo-toa, quaggoths, and troglodytes—often serve illithid masters. Githyanki and githzerai have a long adversarial history with mind flayers and bear the scars of illithid manipulation.

### Mind Flayer Colonies

Mind flayers work as lone schemers, in mysterious cabals, or as part of worlds-spanning illithid conspiracies. In groups, mind flayers work toward bizarre agendas organized by an elder brain—a massive, brain-like being with incredible psionic powers. Without such a leader, groups of mind flayers fall to self-destructive squabbling. Roll on or choose a result from the Mind Flayer Machinations table to inspire an illithid conclave's plots.

**Mind Flayer Machinations**

| dice: 1d6 | The Mind Flayer Colony Seeks To... |
|-----------|------------------------------------|
| 1 | Blot out the sun so their Underdark-dwelling servants can invade the surface. |
| 2 | Create a new monstrous fusion between mind flayers and a legendary monster. |
| 3 | Forge a psionic network uniting illithid colonies. |
| 4 | Replace world leaders with intellect devourers. |
| 5 | Restore a vessel to travel through Wildspace. |
| 6 | Sacrifice the mental energy of a planet's populace to take control of a githyanki bastion. |
^mind-flayer-machinations

## Statblock

```ad-statblock
title: Mind Flayer
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Mind%20Flayer.webp#token)
*Medium aberration, Lawful Evil*

- **Armor Class** 15
- **Hit Points** 99 (`18d8 + 18`)
- **Speed** 30 ft., fly 15 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|12 (+1)|12 (+1)|19 (+4)|17 (+3)|17 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +4, Intelligence +7, Wisdom +6, Charisma +6
- **Skills** [Arcana](z_CLI/rules/skills.md#Arcana) +7, [Insight](z_CLI/rules/skills.md#Insight) +6, [Perception](z_CLI/rules/skills.md#Perception) +6, [Stealth](z_CLI/rules/skills.md#Stealth) +4
- **Senses** [Darkvision](z_CLI/rules/senses.md#Darkvision) 120 ft., passive Perception 16
- **Damage Resistances** psychic
- **Gear** [breastplate](z_CLI/items/breastplate-xphb.md)
- **Languages** Deep Speech, Undercommon; telepathy 120 ft.
- **Challenge** 7

## Traits

***Magic Resistance.*** The mind flayer has [Advantage](z_CLI/rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

## Actions

***Tentacles.*** *Melee Attack Roll:* `+7`, reach 5 ft. *Hit:* 22 (`4d8 + 4`) Psychic damage. If the target is a Medium or smaller creature, it has the [Grappled](z_CLI/rules/conditions.md#Grappled) condition (escape DC 14) from all the mind flayer's tentacles, and the target has the [Stunned](z_CLI/rules/conditions.md#Stunned) condition until the grapple ends.

***Extract Brain.*** *Constitution Saving Throw:* DC 15, one creature that is [Grappled](z_CLI/rules/conditions.md#Grappled) by the mind flayer's Tentacles. *Failure:* 55 (`10d10`) Piercing damage. *Success:* Half damage. *Failure or Success:* If this damage reduces the target to 0 [Hit Points](z_CLI/rules/variant-rules/hit-points-xphb.md), the mind flayer kills it and devours its brain.

***Mind Blast (Recharge 5-6).*** *Intelligence Saving Throw:* DC 15, each creature in a 60-foot [Cone](z_CLI/rules/variant-rules/cone-area-of-effect-xphb.md). *Failure:* 31 (`6d8 + 4`) Psychic damage, and the target has the [Stunned](z_CLI/rules/conditions.md#Stunned) condition until the end of the mind flayer's next turn. *Success:* Half damage only.

***Spellcasting.*** The mind flayer casts one of the following spells, requiring no spell components and using Intelligence as the spellcasting ability (spell save DC 15):

**At will:** [Detect Thoughts](z_CLI/spells/detect-thoughts-xphb.md)

**1/day each:** [Dominate Monster](z_CLI/spells/dominate-monster-xphb.md), [Plane Shift](z_CLI/spells/plane-shift-xphb.md) (self only)
```
^statblock

## Environment

underdark