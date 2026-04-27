---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/21
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/dragon/metallic
aliases:
- "Ancient Copper Dragon"
---
# Ancient Copper Dragon
*Source: Monster Manual (2024) p. 80. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Ancient copper dragons use warmth and reliability to effect change over time. They open their cozy lairs to their friends as havens of learning and laughter for the young and those in need. These dragons watch for and oppose future threats while fostering sanctuaries of simple goodness.

## Copper Dragons

*Dragons of Curiosity and Community*

- **Habitat.** Hill  
- **Treasure.** [Arcana](z_CLI/tables/random-magic-items-arcana.md)  

Relentlessly friendly and curious, most copper dragons view the world as a place of endless wonder and possibility. These gregarious dragons are fonts of patience, hospitality, and humor, and they seek to improve the lives—or, at least, the mood—of those they interact with. If forced to fight to defend themselves or their friends, these dragons favor using their slowing breath and physical attacks to subdue antagonists. Only in cases of extreme peril or emotion do they use their deadly acid breath.

Copper dragons typically live in caverns amid picturesque hills and rock formations—particularly those that are prominent landmarks. These dragons collect gifts, though they have little interest in treasure without meaning, no matter how valuable it is. To them, thoughtfully given presents and the feelings or memories they symbolize are more important than masterpieces or magical relics.

### Copper Dragon Lairs

Copper dragons typically inhabit multi-chamber caves and renovated ruins.

## Statblock

```ad-statblock
title: Ancient Copper Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Ancient%20Copper%20Dragon.webp#token)
*Gargantuan dragon (metallic), Chaotic Good*

- **Armor Class** 21
- **Hit Points** 367 (`21d20 + 147`)
- **Speed** 40 ft., climb 40 ft., fly 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|27 (+8)|12 (+1)|25 (+7)|20 (+5)|17 (+3)|22 (+6)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +8, Wisdom +10
- **Skills** [Deception](z_CLI/rules/skills.md#Deception) +13, [Perception](z_CLI/rules/skills.md#Perception) +17, [Stealth](z_CLI/rules/skills.md#Stealth) +8
- **Senses** [Blindsight](z_CLI/rules/senses.md#Blindsight) 60 ft., [Darkvision](z_CLI/rules/senses.md#Darkvision) 120 ft., passive Perception 27
- **Damage Immunities** acid
- **Languages** Common, Draconic
- **Challenge** 21

## Traits

***Legendary Resistance (4/Day, or 5/Day in Lair).*** If the dragon fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Slowing Breath or (B) Spellcasting to cast [Mind Spike](z_CLI/spells/mind-spike-xphb.md) (level 5 version).

***Rend.*** *Melee Attack Roll:* `+15`, reach 15 ft. *Hit:* 19 (`2d10 + 8`) Slashing damage plus 9 (`2d8`) Acid damage.

***Acid Breath (Recharge 5-6).*** *Dexterity Saving Throw:* DC 22, each creature in an 90-foot-long, 10-foot-wide [Line](z_CLI/rules/variant-rules/line-area-of-effect-xphb.md). *Failure:* 63 (`14d8`) Acid damage. *Success:* Half damage.

***Slowing Breath.*** *Constitution Saving Throw:* DC 22, each creature in a 90-foot [Cone](z_CLI/rules/variant-rules/cone-area-of-effect-xphb.md). *Failure:* The target can't take Reactions; its [Speed](z_CLI/rules/variant-rules/speed-xphb.md) is halved; and it can take either an action or a [Bonus Action](z_CLI/rules/variant-rules/bonus-action-xphb.md) on its turn, not both. This effect lasts until the end of its next turn.

***Spellcasting.*** The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 21):

**At will:** [Detect Magic](z_CLI/spells/detect-magic-xphb.md), [Mind Spike](z_CLI/spells/mind-spike-xphb.md) (level 5 version), [Minor Illusion](z_CLI/spells/minor-illusion-xphb.md), [Shapechange](z_CLI/spells/shapechange-xphb.md) (Beast or Humanoid form only, no [Temporary Hit Points](z_CLI/rules/variant-rules/temporary-hit-points-xphb.md) gained from the spell, and no Concentration or [Temporary Hit Points](z_CLI/rules/variant-rules/temporary-hit-points-xphb.md) required to maintain the spell)

**1/day each:** [Greater Restoration](z_CLI/spells/greater-restoration-xphb.md), [Major Image](z_CLI/spells/major-image-xphb.md), [Project Image](z_CLI/spells/project-image-xphb.md)

## Legendary Actions

Legendary Action Uses: 3 (4 in Lair). Immediately after another creature's turn, the dragon can expend a use to take one of the following actions. The dragon regains all expended uses at the start of each of its turns.

***Giggling Magic.*** *Charisma Saving Throw:* DC 21, one creature the dragon can see within 120 feet. *Failure:* 31 (`9d6`) Psychic damage. Until the end of its next turn, the target rolls `1d8` whenever it makes an ability check or attack roll and subtracts the number rolled from the [D20 Test](z_CLI/rules/variant-rules/d20-test-xphb.md). *Failure or Success:* The dragon can't take this action again until the start of its next turn.

***Mind Jolt.*** The dragon uses Spellcasting to cast [Mind Spike](z_CLI/spells/mind-spike-xphb.md) (level 5 version). The dragon can't take this action again until the start of its next turn.

***Pounce.*** The dragon moves up to half its [Speed](z_CLI/rules/variant-rules/speed-xphb.md), and it makes one Rend attack.

![Copper Dragon](z_CLI/bestiary/legendary-group/copper-dragon-xmm.md)
```
^statblock

## Environment

hill