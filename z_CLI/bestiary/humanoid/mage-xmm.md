---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid/wizard
aliases:
- "Mage"
---
# Mage
*Source: Monster Manual (2024) p. 199. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Mages are accomplished spellcasters whose lives have been shaped by magic. They can use their powers to defend or dominate other creatures, or they could focus on magical research and unlocking mystical secrets.

## Mages

*Magical Scholars and Spellcasters*

- **Habitat.** Any  
- **Treasure.** [Arcana](z_CLI/tables/random-magic-items-arcana.md), Individual  

Mages are magical wonder-workers, ranging from spellcasting overlords to reclusive witches. They study mystical secrets and possess insight into monsters, legends, omens, and other lore. Mages often gather allies or hire assistants to aid them in their research or to attain magical might.

Roll on or choose a result from the Mage Roles table to inspire different sorts of mages.

**Mage Roles**

| dice: 1d10 | The Mage Is... |
|------------|----------------|
| 1 | An astronomer who draws magic from stars. |
| 2 | An author who writes about the occult. |
| 3 | A magical engineer who creates wonders. |
| 4 | An oracle who interprets omens. |
| 5 | A prodigy with a remarkable magical heritage. |
| 6 | A psion whose powers manifest as spells. |
| 7 | A scholar investigating ancient lore. |
| 8 | A soothsayer who advises rulers. |
| 9 | A war mage who aids soldiers in battle. |
| 10 | A witch who shares secret wisdom. |
^mage-roles

> [!quote] A quote from Nathor, Thayan Refugee  
> 
> Have you gazed on the Runes of Chaos, held the Death Moon Orb in your trembling hands, entered the Devouring Portal and walked the Paths of the Doomed, or sat at the left hand of Szass Tam during the Ritual of Twin Burnings? No? Then speak not to me of wizards. Speak not to me of Thay.


## Statblock

```ad-statblock
title: Mage
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Mage.webp#token)
*Small or Medium humanoid (wizard), Neutral*

- **Armor Class** 15
- **Hit Points** 81 (`18d8`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 9 (-1)|14 (+2)|11 (+0)|17 (+3)|12 (+1)|11 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +6, Wisdom +4
- **Skills** [Arcana](z_CLI/rules/skills.md#Arcana) +6, [History](z_CLI/rules/skills.md#History) +6, [Perception](z_CLI/rules/skills.md#Perception) +4
- **Senses** passive Perception 14
- **Gear** [wand](z_CLI/items/wand-xphb.md)
- **Languages** Common and any three languages
- **Challenge** 6

## Actions

***Multiattack.*** The mage makes three Arcane Burst attacks.

***Arcane Burst.*** *Melee  or Ranged Attack Roll:* `+6`, reach 5 ft. or range 120 ft. *Hit:* 16 (`3d8 + 3`) Force damage.

***Spellcasting.*** The mage casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 14):

**At will:** [Detect Magic](z_CLI/spells/detect-magic-xphb.md), [Light](z_CLI/spells/light-xphb.md), [Mage Armor](z_CLI/spells/mage-armor-xphb.md) (included in AC), [Mage Hand](z_CLI/spells/mage-hand-xphb.md), [Prestidigitation](z_CLI/spells/prestidigitation-xphb.md)

**2/day each:** [Fireball](z_CLI/spells/fireball-xphb.md) (level 4 version), [Invisibility](z_CLI/spells/invisibility-xphb.md)

**1/day each:** [Cone of Cold](z_CLI/spells/cone-of-cold-xphb.md), [Fly](z_CLI/spells/fly-xphb.md)

## Bonus Actions

***Misty Step (3/Day).*** The mage casts [Misty Step](z_CLI/spells/misty-step-xphb.md), using the same spellcasting ability as Spellcasting.


## Reactions

***Protective Magic (3/Day).*** The mage casts [Counterspell](z_CLI/spells/counterspell-xphb.md) or [Shield](z_CLI/spells/shield-xphb.md) in response to the spell's trigger, using the same spellcasting ability as Spellcasting.

```
^statblock

## Environment

any