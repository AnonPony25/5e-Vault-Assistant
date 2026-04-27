---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/shadowfell
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
aliases:
- "Wight"
---
# Wight
*Source: Monster Manual (2024) p. 332. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Wight

*Life-Leeching Corpse Warrior*

- **Habitat.** Desert, Planar (Shadowfell), Swamp, Underdark, Urban  
- **Treasure.** [Armaments](z_CLI/tables/random-magic-items-armaments.md)  

Wights are the withered corpses of relentless warriors whose wickedness sustains them beyond death. Unlike mere zombies, they retain the memories and evil agendas they harbored in life.

After dying and returning from the grave, a wight continues its villainous ways, but it is now driven by a hunger for life. A wight drains living essence through its attacks. Humanoids slain by a wight's life-sapping grip reanimate a day later and serve the wight as obedient zombies.

Wights might return from the dead for a multitude of sinister reasons. Roll on or choose a result from the Wight Motives table to inspire why a wight plagues the living.

**Wight Motives**

| dice: 1d8 | The Wight Returned from the Dead To... |
|-----------|----------------------------------------|
| 1 | Challenge anyone who passes near its grave on a certain cursed night. |
| 2 | Conquer the land it believes it should rule. |
| 3 | Continue the crimes it was executed for. |
| 4 | Follow the foul master it served in life. |
| 5 | Honor an oath it left unfulfilled in life. |
| 6 | Obey the cult or deity that gave it unlife. |
| 7 | Prove it was the greatest warrior to ever live. |
| 8 | Seek its stolen heart or other treasure. |
^wight-motives

```ad-statblock
title: Wight
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Wight.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 14
- **Hit Points** 82 (`11d8 + 33`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|14 (+2)|16 (+3)|10 (+0)|13 (+1)|15 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** [Perception](z_CLI/rules/skills.md#Perception) +3, [Stealth](z_CLI/rules/skills.md#Stealth) +4
- **Senses** [Darkvision](z_CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 13
- **Damage Resistances** necrotic
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](z_CLI/rules/conditions.md#Exhaustion), [poisoned](z_CLI/rules/conditions.md#Poisoned)
- **Gear** [studded leather armor](z_CLI/items/studded-leather-armor-xphb.md)
- **Languages** Common plus one other language
- **Challenge** 3

## Traits

***Sunlight Sensitivity.*** While in sunlight, the wight has [Disadvantage](z_CLI/rules/variant-rules/disadvantage-xphb.md) on ability checks and attack rolls.

## Actions

***Multiattack.*** The wight makes two attacks, using Necrotic Sword or Necrotic Bow in any combination. It can replace one attack with a use of Life Drain.

***Necrotic Sword.*** *Melee Attack Roll:* `+4`, reach 5 ft. *Hit:* 6 (`1d8 + 2`) Slashing damage plus 4 (`1d8`) Necrotic damage.

***Necrotic Bow.*** *Ranged Attack Roll:* `+4`, range 150/600 ft. *Hit:* 6 (`1d8 + 2`) Piercing damage plus 4 (`1d8`) Necrotic damage.

***Life Drain.*** *Constitution Saving Throw:* DC 13, one creature within 5 feet. *Failure:* 6 (`1d8 + 2`) Necrotic damage, and the target's [Hit Point](z_CLI/rules/variant-rules/hit-points-xphb.md) maximum decreases by an amount equal to the damage taken.

A Humanoid slain by this attack rises 24 hours later as a [Zombie](z_CLI/bestiary/undead/zombie-xmm.md) under the wight's control, unless the Humanoid is restored to life or its body is destroyed. The wight can have no more than twelve zombies under its control at a time.
```
^statblock

## Environment

desert, planar, shadowfell, swamp, underdark, urban