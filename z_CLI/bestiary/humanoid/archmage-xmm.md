---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid/wizard
aliases:
- "Archmage"
---
# Archmage
*Source: Monster Manual (2024) p. 199. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Archmages have mastered incredible magical power. While some use their magic to protect the world, others become tyrants or pursue forbidden secrets. Many archmages retain magical servants and collect magic items and occult lore.

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
title: Archmage
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Archmage.webp#token)
*Small or Medium humanoid (wizard), Neutral*

- **Armor Class** 17
- **Hit Points** 170 (`31d8 + 31`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|14 (+2)|12 (+1)|20 (+5)|15 (+2)|16 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +9, Wisdom +6
- **Skills** [Arcana](z_CLI/rules/skills.md#Arcana) +13, [History](z_CLI/rules/skills.md#History) +9, [Perception](z_CLI/rules/skills.md#Perception) +6
- **Senses** passive Perception 16
- **Damage Immunities** psychic
- **Condition Immunities** [charmed](z_CLI/rules/conditions.md#Charmed) (with Mind Blank)
- **Gear** [wand](z_CLI/items/wand-xphb.md)
- **Languages** Common plus five other languages
- **Challenge** 12

## Traits

***Magic Resistance.*** The archmage has [Advantage](z_CLI/rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The archmage makes four Arcane Burst attacks.

***Arcane Burst.*** *Melee  or Ranged Attack Roll:* `+9`, reach 5 ft. or range 150 ft. *Hit:* 27 (`4d10 + 5`) Force damage.

***Spellcasting.*** The archmage casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 17):

**At will:** [Detect Magic](z_CLI/spells/detect-magic-xphb.md), [Detect Thoughts](z_CLI/spells/detect-thoughts-xphb.md), [Disguise Self](z_CLI/spells/disguise-self-xphb.md), [Invisibility](z_CLI/spells/invisibility-xphb.md), [Light](z_CLI/spells/light-xphb.md), [Mage Armor](z_CLI/spells/mage-armor-xphb.md) (included in AC), [Mage Hand](z_CLI/spells/mage-hand-xphb.md), [Prestidigitation](z_CLI/spells/prestidigitation-xphb.md)

**2/day each:** [Fly](z_CLI/spells/fly-xphb.md), [Lightning Bolt](z_CLI/spells/lightning-bolt-xphb.md) (level 7 version)

**1/day each:** [Cone of Cold](z_CLI/spells/cone-of-cold-xphb.md) (level 9 version), [Mind Blank](z_CLI/spells/mind-blank-xphb.md) (cast before combat), [Scrying](z_CLI/spells/scrying-xphb.md), [Teleport](z_CLI/spells/teleport-xphb.md)

## Bonus Actions

***Misty Step (3/Day).*** The mage casts [Misty Step](z_CLI/spells/misty-step-xphb.md), using the same spellcasting ability as Spellcasting.


## Reactions

***Protective Magic (3/Day).*** The archmage casts [Counterspell](z_CLI/spells/counterspell-xphb.md) or [Shield](z_CLI/spells/shield-xphb.md) in response to the spell's trigger, using the same spellcasting ability as Spellcasting.

```
^statblock

## Environment

any