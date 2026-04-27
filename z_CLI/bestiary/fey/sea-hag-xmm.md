---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/underwater
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
aliases:
- "Sea Hag"
---
# Sea Hag
*Source: Monster Manual (2024) p. 271. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Sea Hag

*Hag of Despair and the Dismal Deep*

- **Habitat.** Coastal, Underwater  
- **Treasure.** [Arcana](z_CLI/tables/random-magic-items-arcana.md)  

Sea hags loathe peace and beauty. Bitter, jealous creatures, they spread chaos and undermine joy however they can, undertaking elaborate deceptions to sow discord for its own sake. The hags' true forms are supernaturally vile, and their baleful gazes can strike down creatures [frightened](z_CLI/rules/conditions.md#Frightened) by their appearance.

Sea hags cloak themselves in illusions to work their schemes. Roll on or choose a result from the Sea Hag Disguises table to inspire a sea hag's illusion and how they might use it to wreak chaos and destruction.

**Sea Hag Disguises**

| dice: 1d6 | The Sea Hag Takes the Form of A... |
|-----------|------------------------------------|
| 1 | Captive and claims nearby villagers bound them and left them to drown. |
| 2 | Castaway and shares a cursed item's location with would-be rescuers. |
| 3 | Healer and passes off poisons as medicine. |
| 4 | Panic-spreading prophesier of doom. |
| 5 | Ship captain and delivers passengers to the hag's pet sea monster. |
| 6 | Wounded sailor and claims their ship was destroyed by merfolk or other peaceful people. |
^sea-hag-disguises

```ad-statblock
title: Sea Hag
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Sea%20Hag.webp#token)
*Medium fey, Chaotic Evil*

- **Armor Class** 14
- **Hit Points** 52 (`7d8 + 21`)
- **Speed** 30 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|13 (+1)|16 (+3)|12 (+1)|12 (+1)|13 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** [Darkvision](z_CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 11
- **Languages** Common, Giant, Primordial (Aquan)
- **Challenge** 2

## Traits

***Coven Magic.*** While within 30 feet of at least two hag allies, the hag can cast one of the following spells, requiring no Material components, using the spell's normal casting time, and using Intelligence as the spellcasting ability (spell save DC 11): [Augury](z_CLI/spells/augury-xphb.md), [Find Familiar](z_CLI/spells/find-familiar-xphb.md), [Identify](z_CLI/spells/identify-xphb.md), [Locate Object](z_CLI/spells/locate-object-xphb.md), [Scrying](z_CLI/spells/scrying-xphb.md), or [Unseen Servant](z_CLI/spells/unseen-servant-xphb.md). The hag must finish a [Long Rest](z_CLI/rules/variant-rules/long-rest-xphb.md) before using this trait to cast that spell again.


***Amphibious.*** The hag can breathe air and water.

***Vile Appearance.*** *Wisdom Saving Throw:* DC 11, any Beast or Humanoid that starts its turn within 30 feet of the hag and can see the hag's true form. *Failure:* The target has the [Frightened](z_CLI/rules/conditions.md#Frightened) condition until the start of its next turn. *Success:* The target is immune to this hag's Vile Appearance for 24 hours.

## Actions

***Claw.*** *Melee Attack Roll:* `+5`, reach 5 ft. *Hit:* 10 (`2d6 + 3`) Slashing damage.

***Death Glare (Recharge 5-6).*** *Wisdom Saving Throw:* DC 11, one [Frightened](z_CLI/rules/conditions.md#Frightened) creature the hag can see within 30 feet. *Failure:* If the target has 20 [Hit Points](z_CLI/rules/variant-rules/hit-points-xphb.md) or fewer, it drops to 0 [Hit Points](z_CLI/rules/variant-rules/hit-points-xphb.md). Otherwise, the target takes 13 (`3d8`) Psychic damage.

***Illusory Appearance.*** The hag casts [Disguise Self](z_CLI/spells/disguise-self-xphb.md), using Constitution as the spellcasting ability (spell save DC 13). The spell's duration is 24 hours.

```
^statblock

## Environment

coastal, underwater