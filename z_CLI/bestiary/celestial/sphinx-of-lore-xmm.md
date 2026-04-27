---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/upper
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/celestial
aliases:
- "Sphinx of Lore"
---
# Sphinx of Lore
*Source: Monster Manual (2024) p. 293. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Sphinxes of lore each know a great secret and protect it all costs. This truth might take the form of an ancient text, a magical puzzle, or a path to another world. These sphinxes might gain reputations as sages or oracles, but they typically dwell far from civilization.

## Sphinxes

*Collectors and Keepers of Secrets*

- **Habitat.** Desert, Planar (Upper Planes)  
- **Treasure.** [Arcana](z_CLI/tables/random-magic-items-arcana.md)  

Sphinxes protect the secrets of the multiverse. Formed from the spirits of sages and explorers, sphinxes know the power of truth and the importance of preserving it. They share their wisdom only with those who prove themselves wise or overcome tests of worthiness, such as riddles or battles with dangerous beasts. Through their existences, sphinxes might change form as they gain more nuanced understanding of cosmic enigmas.

### Sphinx Lairs

Sphinxes typically dwell in places that hold great knowledge or prophetic magic.

> [!quote]  
> 
> Round she is, yet flat as a board
> 
> Altar of the Lupine Lords
> 
> Jewel on black velvet, pearl in the sea
> 
> Unchanged but e'erchanging eternally

> [!note]
> Answer to the riddle of White Plume Mountain: The Moon.

## Statblock

```ad-statblock
title: Sphinx of Lore
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Sphinx%20of%20Lore.webp#token)
*Large celestial, Lawful Neutral*

- **Armor Class** 17
- **Hit Points** 170 (`20d10 + 60`)
- **Speed** 40 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|15 (+2)|16 (+3)|18 (+4)|18 (+4)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** [Arcana](z_CLI/rules/skills.md#Arcana) +12, [History](z_CLI/rules/skills.md#History) +12, [Perception](z_CLI/rules/skills.md#Perception) +8, [Religion](z_CLI/rules/skills.md#Religion) +12
- **Senses** [Truesight](z_CLI/rules/senses.md#Truesight) 120 ft., passive Perception 18
- **Damage Resistances** necrotic, radiant
- **Damage Immunities** psychic
- **Condition Immunities** [charmed](z_CLI/rules/conditions.md#Charmed), [frightened](z_CLI/rules/conditions.md#Frightened)
- **Languages** Celestial, Common
- **Challenge** 11

## Traits

***Inscrutable.*** No magic can observe the sphinx remotely or detect its thoughts without its permission. Wisdom ([Insight](z_CLI/rules/skills.md#Insight)) checks made to ascertain its intentions or sincerity are made with [Disadvantage](z_CLI/rules/variant-rules/disadvantage-xphb.md).

***Legendary Resistance (3/Day, or 4/Day in Lair).*** If the sphinx fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** The sphinx makes three Claw attacks.

***Claw.*** *Melee Attack Roll:* `+8`, reach 5 ft. *Hit:* 14 (`3d6 + 4`) Slashing damage.

***Mind-Rending Roar (Recharge 5-6).*** *Wisdom Saving Throw:* DC 16, each enemy in a 300-foot [Emanation](z_CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from the sphinx. *Failure:* 35 (`10d6`) Psychic damage, and the target has the [Incapacitated](z_CLI/rules/conditions.md#Incapacitated) condition until the start of the sphinx's next turn.

***Spellcasting.*** The sphinx casts one of the following spells, requiring no Material components and using Intelligence as the spellcasting ability (spell save DC 16):

**At will:** [Detect Magic](z_CLI/spells/detect-magic-xphb.md), [Identify](z_CLI/spells/identify-xphb.md), [Mage Hand](z_CLI/spells/mage-hand-xphb.md), [Minor Illusion](z_CLI/spells/minor-illusion-xphb.md), [Prestidigitation](z_CLI/spells/prestidigitation-xphb.md)

**1/day each:** [Dispel Magic](z_CLI/spells/dispel-magic-xphb.md), [Legend Lore](z_CLI/spells/legend-lore-xphb.md), [Locate Object](z_CLI/spells/locate-object-xphb.md), [Plane Shift](z_CLI/spells/plane-shift-xphb.md), [Remove Curse](z_CLI/spells/remove-curse-xphb.md), [Tongues](z_CLI/spells/tongues-xphb.md)

## Legendary Actions

Legendary Action Uses: 3 (4 in Lair). Immediately after another creature's turn, the sphinx of lore can expend a use to take one of the following actions. The sphinx of lore regains all expended uses at the start of each of its turns.

***Arcane Prowl.*** The sphinx can teleport up to 30 feet to an unoccupied space it can see, and it makes one Claw attack.

***Weight of Years.*** *Constitution Saving Throw:* DC 16, one creature the sphinx can see within 120 feet. *Failure:* The target gains 1 [Exhaustion](z_CLI/rules/conditions.md#Exhaustion) level. While the target has any [Exhaustion](z_CLI/rules/conditions.md#Exhaustion) levels, it appears `3d10` years older. *Failure or Success:* The sphinx can't take this action again until the start of its next turn.

![Sphinx](z_CLI/bestiary/legendary-group/sphinx-xmm.md)
```
^statblock

## Environment

desert, planar, upper