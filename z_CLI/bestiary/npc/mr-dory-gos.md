---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/gos
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration
aliases:
- "Mr. Dory"
---
# Mr. Dory
*Source: Ghosts of Saltmarsh p. 246*  

One of the four councillors who rule the Styes, Mr. Dory hides his cursed nature in plain sight. His rare, liquid-sensitive "skin condition" is actually a form of the same aboleth affliction that creates skum, though Dory's condition is not as severe, and he has managed to retain his free will.

```ad-statblock
title: Mr. Dory
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GoS/Mr.%20Dory.webp#token)
*Medium aberration, Chaotic Evil*

- **Armor Class** 18 ([studded leather](z_CLI/items/studded-leather-armor-xphb.md), [shield](z_CLI/items/shield-xphb.md))
- **Hit Points** 170 (`20d8 + 80`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|20 (+5)|19 (+4)|14 (+2)|14 (+2)|16 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +8, Wisdom +6
- **Skills** [Athletics](z_CLI/rules/skills.md#Athletics) +5, [Perception](z_CLI/rules/skills.md#Perception) +6, [Stealth](z_CLI/rules/skills.md#Stealth) +9
- **Senses** [darkvision](z_CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 16
- **Damage Immunities** necrotic
- **Gear** [rapier](z_CLI/items/rapier-xphb.md)
- **Languages** Abyssal, Common, Deep Speech, telepathy 60 ft.
- **Challenge** 10

## Traits

***Innate Spellcasting.*** Mr. Dory's innate spellcasting ability is Charisma (save DC 15, `+7` to hit with spell attacks). Mr. Dory can innately cast the following spells, requiring no material components:

**At will:** [detect magic](z_CLI/spells/detect-magic-xphb.md), [detect thoughts](z_CLI/spells/detect-thoughts-xphb.md), [invisibility](z_CLI/spells/invisibility-xphb.md) (self only)

**2/day each:** [fear](z_CLI/spells/fear-xphb.md), [fireball](z_CLI/spells/fireball-xphb.md), [fly](z_CLI/spells/fly-xphb.md)

**1/day each:** [cloudkill](z_CLI/spells/cloudkill-xphb.md), [etherealness](z_CLI/spells/etherealness-xphb.md)

***Magic Resistance.*** Mr. Dory has advantage on saving throws against spells and other magical effects.

***Water Dependency.*** Mr. Dory takes 6 (`1d12`) acid damage at the end of every hour he goes without exposure to water.

## Actions

***Multiattack.*** Mr. Dory makes three attacks with his rapier.

***Rapier.*** *Melee Weapon Attack:* `+9` to hit, reach 5 ft., one target. *Hit:* 9 (`1d8 + 5`) piercing damage and 7 (`2d6`) necrotic damage.

***Eye of Corruption (Recharge 5-6).*** Mr. Dory glares at a creature he can see within 30 feet of him. The target must make a DC 15 Constitution saving throw. On a failed save, it takes 27 (`5d10`) necrotic damage and 27 (`5d10`) poison damage and then gains vulnerability to both necrotic and poison damage for 1 minute. On a successful save, it takes half damage and does not gain the vulnerabilities.
```
^statblock