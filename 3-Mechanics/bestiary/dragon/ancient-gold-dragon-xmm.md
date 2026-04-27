---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/24
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/dragon/metallic
aliases:
- "Ancient Gold Dragon"
---
# Ancient Gold Dragon
*Source: Monster Manual (2024) p. 146. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Ancient gold dragons are wise and mysterious. Many aid virtuous groups, guiding them in secret or patronizing them from afar. Only when stakes are at their highest do ancient gold dragons reveal themselves in all their majesty.

## Gold Dragons

*Dragons of Hope and Majesty*

- **Habitat.** Forest, Grassland  
- **Treasure.** [Arcana](z_CLI/tables/random-magic-items-arcana.md)  

Gold dragons work to make the world a better place. The most powerful of the metallic dragons, these awe-inspiring dragons strive to protect that which is good and bend fate toward a brighter future. Their kind dispositions don't prevent gold dragons from engaging in combat when necessary, though, and they exhale brilliant flames and weakening magic to rout their foes.

Gold dragons favor grasslands and pristine forests, frequently dwelling near awe-inspiring natural wonders or guarding monuments from ancient civilizations. In their lairs, gold dragons hoard coins and gems, but they frequently put their treasure to use in pursuit of greater goals. They often use their riches to buy rare lore books, pay informants, or patronize idealistic adventurers.

### Gold Dragon Lairs

Gold dragons make their homes in places of natural and magical wonder.

## Statblock

```ad-statblock
title: Ancient Gold Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Ancient%20Gold%20Dragon.webp#token)
*Gargantuan dragon (metallic), Lawful Good*

- **Armor Class** 22
- **Hit Points** 546 (`28d20 + 252`)
- **Speed** 40 ft., fly 80 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|30 (+10)|14 (+2)|29 (+9)|18 (+4)|17 (+3)|28 (+9)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +9, Wisdom +10
- **Skills** [Insight](z_CLI/rules/skills.md#Insight) +10, [Perception](z_CLI/rules/skills.md#Perception) +17, [Persuasion](z_CLI/rules/skills.md#Persuasion) +16, [Stealth](z_CLI/rules/skills.md#Stealth) +9
- **Senses** [Blindsight](z_CLI/rules/senses.md#Blindsight) 60 ft., [Darkvision](z_CLI/rules/senses.md#Darkvision) 120 ft., passive Perception 27
- **Damage Immunities** fire
- **Languages** Common, Draconic
- **Challenge** 24

## Traits

***Amphibious.*** The dragon can breathe air and water.

***Legendary Resistance (4/Day, or 5/Day in Lair).*** If the dragon fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Spellcasting to cast [Guiding Bolt](z_CLI/spells/guiding-bolt-xphb.md) (level 4 version) or (B) Weakening Breath.

***Rend.*** *Melee Attack Roll:* `+17` to hit, reach 15 ft. *Hit:* 19 (`2d8 + 10`) Slashing damage plus 9 (`2d8`) Fire damage.

***Fire Breath (Recharge 5-6).*** *Dexterity Saving Throw:* DC 24, each creature in a 90-foot [Cone](z_CLI/rules/variant-rules/cone-area-of-effect-xphb.md). *Failure:* 71 (`13d10`) Fire damage. *Success:* Half damage.

***Weakening Breath.*** *Strength Saving Throw:* DC 24, each creature that isn't currently affected by this breath in a 90-foot [Cone](z_CLI/rules/variant-rules/cone-area-of-effect-xphb.md). *Failure:* The target has [Disadvantage](z_CLI/rules/variant-rules/disadvantage-xphb.md) on Strength-based [D20 Tests](z_CLI/rules/variant-rules/d20-test-xphb.md) and subtracts 5 (`1d10`) from its damage rolls. It repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

***Spellcasting.*** The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 24, `+16` to hit with spell attacks):

**At will:** [Detect Magic](z_CLI/spells/detect-magic-xphb.md), [Guiding Bolt](z_CLI/spells/guiding-bolt-xphb.md) (level 4 version), [Shapechange](z_CLI/spells/shapechange-xphb.md) (Beast or Humanoid form only, no [Temporary Hit Points](z_CLI/rules/variant-rules/temporary-hit-points-xphb.md) gained from the spell, and no Concentration or [Temporary Hit Points](z_CLI/rules/variant-rules/temporary-hit-points-xphb.md) required to maintain the spell)

**1/day each:** [Flame Strike](z_CLI/spells/flame-strike-xphb.md) (level 6 version), [Word of Recall](z_CLI/spells/word-of-recall-xphb.md), [Zone of Truth](z_CLI/spells/zone-of-truth-xphb.md)

## Legendary Actions

Legendary Action Uses: 3 (4 in Lair). Immediately after another creature's turn, the dragon can expend a use to take one of the following actions. The dragon regains all expended uses at the start of each of its turns.

***Banish.*** *Charisma Saving Throw:* DC 24, one creature the dragon can see within 120 feet. *Failure:* 24 (`7d6`) Force damage, and the target has the [Incapacitated](z_CLI/rules/conditions.md#Incapacitated) condition and is transported to a harmless demiplane until the start of the dragon's next turn, at which point it reappears in an unoccupied space of the dragon's choice within 120 feet of the dragon. *Failure or Success:* The dragon can't take this action again until the start of its next turn.

***Guiding Light.*** The dragon uses Spellcasting to cast [Guiding Bolt](z_CLI/spells/guiding-bolt-xphb.md) (level 4 version).

***Pounce.*** The dragon moves up to half its [Speed](z_CLI/rules/variant-rules/speed-xphb.md), and it makes one Rend attack.

![Gold Dragon](z_CLI/bestiary/legendary-group/gold-dragon-xmm.md)
```
^statblock

## Environment

forest, grassland