---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/environment/feywild
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
aliases:
- "Satyr Revelmaster"
---
# Satyr Revelmaster
*Source: Monster Manual (2024) p. 268*  

Satyr revelmasters use magical music to change the moods of other creatures. They do so to keep their celebrations exciting and to ward off foes.

## Satyrs

*Horned and Hoofed Revelers*

- **Habitat.** Forest, Planar (Feywild)  
- **Treasure.** [Implements](z_CLI/tables/random-magic-items-implements.md)  

Satyrs embody the untamed joys of the wilderness. They indulge in sprees of merrymaking—eating, drinking, performing, fighting, and frolicking.

## Statblock

```ad-statblock
title: Satyr Revelmaster
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Satyr%20Revelmaster.webp#token)
*Medium fey, Chaotic Neutral*

- **Armor Class** 17
- **Hit Points** 82 (`15d8 + 15`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|18 (+4)|12 (+1)|12 (+1)|14 (+2)|17 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +7, Wisdom +5
- **Skills** [Acrobatics](z_CLI/rules/skills.md#Acrobatics) +7, [Perception](z_CLI/rules/skills.md#Perception) +5, [Performance](z_CLI/rules/skills.md#Performance) +9
- **Senses** passive Perception 15
- **Languages** Common, Elvish, Sylvan
- **Challenge** 6

## Traits

***Magic Resistance.*** The satyr has [Advantage](z_CLI/rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The satyr makes three Prance attacks.

***Prance.*** *Melee Attack Roll:* `+7`, reach 5 ft. *Hit:* 13 (`2d8 + 4`) Bludgeoning damage, and the target has the [Charmed](z_CLI/rules/conditions.md#Charmed) condition until the start of the satyr's next turn.

***Fey Melody (Recharge 4-6).*** The satyr conjures a charming or frightening song. *Wisdom Saving Throw:* DC 14, each enemy in a 60-foot [Emanation](z_CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from the satyr. *Failure:* The target is subjected to the song's effect:

- **Charming.** The target has the [Charmed](z_CLI/rules/conditions.md#Charmed) condition for 1 minute. While [Charmed](z_CLI/rules/conditions.md#Charmed), the target has the [Incapacitated](z_CLI/rules/conditions.md#Incapacitated) condition and uses all its movement to dance in place. The effect ends on the target if it takes any damage.  
- **Frightening.** 10 (`2d6 + 3`) Psychic damage, and the target has the [Frightened](z_CLI/rules/conditions.md#Frightened) condition for 1 minute. If the target ends its turn out of line of sight from the satyr, the condition ends on it.  
```
^statblock

## Environment

forest, planar, feywild