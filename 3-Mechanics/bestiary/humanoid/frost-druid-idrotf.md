---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/idrotf
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
aliases:
- "Frost Druid"
---
# Frost Druid
*Source: Icewind Dale: Rime of the Frostmaiden p. 288*  

Frost druids are solitary defenders of nature and the natural enemies of civilization in the North. They seek to preserve the arctic wilderness by destroying outsiders who cross their path. Each patrols its territory in the guise of an arctic fox, a mountain goat, a snowy owl, or a wolf, reverting to human form only when it attacks. Clever ambushers, they use [hallucinatory terrain](z_CLI/spells/hallucinatory-terrain-xphb.md) spells to create illusory snowdrifts under which they can hide, or to obscure pools covered by thin ice through which others might fall.

## Awakened Companions

A frost druid is often accompanied by one or more beasts, shrubs, or evergreen trees that it has made sentient using the [awaken](z_CLI/spells/awaken-xphb.md) spell. These druids favor polar bears and reindeer (use the [elk](z_CLI/bestiary/beast/elk-xmm.md) stat block in the "Monster Manual") as companions, and such creatures typically share the druid's disposition.

## Ice Sickle

A frost druid can carve a sickle out of ice, requiring a total of 24 hours for the work. Bitter cold courses through this weapon while it's in the druid's hands. If the druid dies, the ice sickle melts away. The weapon is otherwise identical to a normal sickle.

## Statblock

```ad-statblock
title: Frost Druid
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Frost%20Druid.webp#token)
*Medium humanoid (human), Any alignment*

- **Armor Class** 13 ([hide armor](z_CLI/items/hide-armor-xphb.md))
- **Hit Points** 67 (`9d8 + 27`)
- **Speed** 40 ft. (wolf form only), burrow 5 ft. (fox form only), climb 30 ft. (goat form only), fly 60 ft. (owl form only)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|13 (+1)|16 (+3)|10 (+0)|16 (+3)| 9 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +3, Wisdom +6
- **Skills** [Nature](z_CLI/rules/skills.md#Nature) +3, [Perception](z_CLI/rules/skills.md#Perception) +6, [Survival](z_CLI/rules/skills.md#Survival) +6
- **Senses** [darkvision](z_CLI/rules/senses.md#Darkvision) 60 ft. (beast form only), passive Perception 16
- **Damage Resistances** cold
- **Gear** [maul](z_CLI/items/maul-xphb.md)
- **Languages** Common, Druidic
- **Challenge** 5

## Traits

***Spellcasting (Humanoid Form Only).*** The druid is a 9th-level spellcaster. Its spellcasting ability is Wisdom (spell save DC 14; `+6` to hit with spell attacks). It has the following druid spells prepared:

**Cantrips (at will):** [druidcraft](z_CLI/spells/druidcraft-xphb.md), [guidance](z_CLI/spells/guidance-xphb.md), [resistance](z_CLI/spells/resistance-xphb.md)

**1st level (4 slots):** [animal friendship](z_CLI/spells/animal-friendship-xphb.md), [fog cloud](z_CLI/spells/fog-cloud-xphb.md), [speak with animals](z_CLI/spells/speak-with-animals-xphb.md)

**2nd level (3 slots):** [animal messenger](z_CLI/spells/animal-messenger-xphb.md), [moonbeam](z_CLI/spells/moonbeam-xphb.md), [pass without trace](z_CLI/spells/pass-without-trace-xphb.md)

**3rd level (3 slots):** [conjure animals](z_CLI/spells/conjure-animals-xphb.md), [sleet storm](z_CLI/spells/sleet-storm-xphb.md), [wind wall](z_CLI/spells/wind-wall-xphb.md)

**4th level (3 slots):** [hallucinatory terrain](z_CLI/spells/hallucinatory-terrain-xphb.md), [ice storm](z_CLI/spells/ice-storm-xphb.md)

**5th level (1 slots):** [awaken](z_CLI/spells/awaken-xphb.md)

## Actions

***Multiattack.*** The druid makes two melee attacks.

***Ice Sickle (Humanoid Form Only).*** *Melee Weapon Attack:* `+4` to hit, reach 5 ft., one target. *Hit:* 3 (`1d4 + 1`) slashing damage plus 5 (`2d4`) cold damage.

***Maul (Beast Form Only).*** *Melee Weapon Attack:* `+4` to hit, reach 5 ft., one target. *Hit:* 3 (`1d4 + 1`) piercing damage.

***Change Shape.*** The druid magically polymorphs into a beast form—fox, mountain goat, owl, or wolf—or back into its humanoid form. Any equipment it is wearing or carrying is absorbed or borne by the beast form (the druid's choice). It reverts to its humanoid form when it dies. The druid's statistics are the same in each form, except where noted in this stat block.
```
^statblock