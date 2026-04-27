---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/upper
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/celestial
aliases:
- "Guardian Naga"
---
# Guardian Naga
*Source: Monster Manual (2024) p. 161. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Guardian Naga

*Enduring Serpentine Lore Keeper*

- **Habitat.** Desert, Forest, Planar (Upper Planes)  
- **Treasure.** [Relics](z_CLI/tables/random-magic-items-relics.md)  

Guardian nagas are immortal, serpentine scholars that possess perfect memories. They collect the histories and lore of those they live among, guarding cultures' stories and passing them on to new generations with infallible accuracy. Guardian nagas that outlive their host civilizations might linger in whatever ruins remain, preserving the civilizations' stories so their lost people might live on.

Roll on or choose a result from the Guardian Naga Lore table to inspire what a naga knows.

**Guardian Naga Lore**

| dice: 1d8 | The Guardian Naga Recalls... |
|-----------|------------------------------|
| 1 | The last words of an ancient sage or leader. |
| 2 | The location of a hidden city or continent. |
| 3 | A magic word, password, or riddle's answer. |
| 4 | The names of all who have told it stories. |
| 5 | An otherwise forgotten ritual or spell. |
| 6 | Recipes using regional ingredients. |
| 7 | Stories of forgotten gods and local spirits. |
| 8 | The vulnerabilities of a legendary monster. |
^guardian-naga-lore

```ad-statblock
title: Guardian Naga
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Guardian%20Naga.webp#token)
*Large celestial, Lawful Good*

- **Armor Class** 18
- **Hit Points** 136 (`16d10 + 48`)
- **Speed** 40 ft., climb 40 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|18 (+4)|16 (+3)|16 (+3)|19 (+4)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +8, Constitution +7, Intelligence +7, Wisdom +8, Charisma +8
- **Skills** [Arcana](z_CLI/rules/skills.md#Arcana) +11, [History](z_CLI/rules/skills.md#History) +11, [Religion](z_CLI/rules/skills.md#Religion) +11
- **Senses** [Darkvision](z_CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 14
- **Damage Immunities** poison
- **Condition Immunities** [charmed](z_CLI/rules/conditions.md#Charmed), [paralyzed](z_CLI/rules/conditions.md#Paralyzed), [poisoned](z_CLI/rules/conditions.md#Poisoned), [restrained](z_CLI/rules/conditions.md#Restrained)
- **Languages** Celestial, Common
- **Challenge** 10

## Traits

***Celestial Restoration.*** If the naga dies, it returns to life in `1d6` days and regains all its [Hit Points](z_CLI/rules/variant-rules/hit-points-xphb.md) unless [Dispel Evil and Good](z_CLI/spells/dispel-evil-and-good-xphb.md) is cast on its remains.

## Actions

***Multiattack.*** The naga makes two Bite attacks. It can replace any attack with a use of Poisonous Spittle.

***Bite.*** *Melee Attack Roll:* `+8`, reach 10 ft. *Hit:* 17 (`2d12 + 4`) Piercing damage plus 22 (`4d10`) Poison damage.

***Poisonous Spittle.*** *Constitution Saving Throw:* DC 16, one creature the naga can see within 60 feet. *Failure:* 31 (`7d8`) Poison damage, and the target has the [Blinded](z_CLI/rules/conditions.md#Blinded) condition until the start of the naga's next turn. *Success:* Half damage only.

***Spellcasting.*** The naga casts one of the following spells, requiring no Somatic or Material components and using Wisdom as the spellcasting ability (spell save DC 16):

**At will:** [Thaumaturgy](z_CLI/spells/thaumaturgy-xphb.md)

**1/day each:** [Clairvoyance](z_CLI/spells/clairvoyance-xphb.md), [Cure Wounds](z_CLI/spells/cure-wounds-xphb.md) (level 6 version), [Flame Strike](z_CLI/spells/flame-strike-xphb.md) (level 6 version), [Geas](z_CLI/spells/geas-xphb.md), [True Seeing](z_CLI/spells/true-seeing-xphb.md)
```
^statblock

## Environment

desert, forest, planar, upper