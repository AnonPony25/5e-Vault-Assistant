---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/23
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/dragon/metallic
aliases:
- "Ancient Silver Dragon"
---
# Ancient Silver Dragon
*Source: Monster Manual (2024) p. 280. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Ancient silver dragons pursue world-wide change. They defend their communities and allies, encouraging them to perform deeds worthy of legend. Some set their sights on other worlds and planes of existence, creating extraplanar alliances or combating multiplanar threats. They might have guises in multiple societies and forge generation-spanning friendships with heroic families or valorous groups.

## Silver Dragons

*Dragons of Courage and Fairness*

- **Habitat.** Mountain, Urban  
- **Treasure.** [Arcana](z_CLI/tables/random-magic-items-arcana.md)  

Silver dragons work to preserve peace and encourage greatness. They try to live as examples of decency while remaining watchful against evil.

Silver dragons typically dwell amid snow-capped mountains, though aspirations and congeniality drive some to instead live among cosmopolitan societies. Disguised as humanoids, they ally with artists, historians, knights, and humble leaders who learn from the past to create better futures.

Silver dragons take inspiration from legendary heroes and have grand ambitions. Many collect treasures that reflect these interests, such as histories, ancient art, and the gear of famous champions.

### Silver Dragon Lairs

Silver dragons typically lair in picturesque mountain retreats or on sculpted cloud "islands."

## Statblock

```ad-statblock
title: Ancient Silver Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Ancient%20Silver%20Dragon.webp#token)
*Gargantuan dragon (metallic), Lawful Good*

- **Armor Class** 22
- **Hit Points** 468 (`24d20 + 216`)
- **Speed** 40 ft., fly 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|30 (+10)|10 (+0)|29 (+9)|18 (+4)|15 (+2)|26 (+8)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +7, Wisdom +9
- **Skills** [History](z_CLI/rules/skills.md#History) +11, [Perception](z_CLI/rules/skills.md#Perception) +16, [Stealth](z_CLI/rules/skills.md#Stealth) +7
- **Senses** [Blindsight](z_CLI/rules/senses.md#Blindsight) 60 ft., [Darkvision](z_CLI/rules/senses.md#Darkvision) 120 ft., passive Perception 26
- **Damage Immunities** cold
- **Languages** Common, Draconic
- **Challenge** 23

## Traits

***Legendary Resistance (4/Day, or 5/Day in Lair).*** If the dragon fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Paralyzing Breath or (B) Spellcasting to cast [Ice Knife](z_CLI/spells/ice-knife-xphb.md) (level 2 version).

***Rend.*** *Melee Attack Roll:* `+17`, reach 15 ft. *Hit:* 19 (`2d8 + 10`) Slashing damage plus 9 (`2d8`) Cold damage.

***Cold Breath (Recharge 5-6).*** *Constitution Saving Throw:* DC 24, each creature in a 90-foot [Cone](z_CLI/rules/variant-rules/cone-area-of-effect-xphb.md). *Failure:* 67 (`15d8`) Cold damage. *Success:* Half damage.

***Paralyzing Breath.*** *Constitution Saving Throw:* DC 24, each creature in a 90-foot [Cone](z_CLI/rules/variant-rules/cone-area-of-effect-xphb.md). *1St Failure:* The target has the [Incapacitated](z_CLI/rules/conditions.md#Incapacitated) condition until the end of its next turn, when it repeats the save. *2Nd Failure:* The target has the [Paralyzed](z_CLI/rules/conditions.md#Paralyzed) condition, and it repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

***Spellcasting.*** The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 23, `+15` to hit with spell attacks):

**At will:** [Detect Magic](z_CLI/spells/detect-magic-xphb.md), [Hold Monster](z_CLI/spells/hold-monster-xphb.md), [Ice Knife](z_CLI/spells/ice-knife-xphb.md) (level 2 version), [Shapechange](z_CLI/spells/shapechange-xphb.md) (Beast or Humanoid form only, no [Temporary Hit Points](z_CLI/rules/variant-rules/temporary-hit-points-xphb.md) gained from the spell, and no Concentration or [Temporary Hit Points](z_CLI/rules/variant-rules/temporary-hit-points-xphb.md) required to maintain the spell)

**1/day each:** [Control Weather](z_CLI/spells/control-weather-xphb.md), [Ice Storm](z_CLI/spells/ice-storm-xphb.md) (level 7 version), [Teleport](z_CLI/spells/teleport-xphb.md), [Zone of Truth](z_CLI/spells/zone-of-truth-xphb.md)

## Legendary Actions

Legendary Action Uses: 3 (4 in Lair). Immediately after another creature's turn, the dragon can expend a use to take one of the following actions. The dragon regains all expended uses at the start of each of its turns.

***Chill.*** The dragon uses Spellcasting to cast [Hold Monster](z_CLI/spells/hold-monster-xphb.md). The dragon can't take this action again until the start of its next turn.

***Cold Gale.*** *Dexterity Saving Throw:* DC 23, each creature in a 60-foot-long, 10-foot-wide [Line](z_CLI/rules/variant-rules/line-area-of-effect-xphb.md). *Failure:* 14 (`4d6`) Cold damage, and the target is pushed up to 30 feet straight away from the dragon. *Success:* Half damage only. *Failure or Success:* The dragon can't take this action again until the start of its next turn.

***Pounce.*** The dragon moves up to half its [Speed](z_CLI/rules/variant-rules/speed-xphb.md), and it makes one Rend attack.

![Silver Dragon](z_CLI/bestiary/legendary-group/silver-dragon-xmm.md)
```
^statblock

## Environment

mountain, urban