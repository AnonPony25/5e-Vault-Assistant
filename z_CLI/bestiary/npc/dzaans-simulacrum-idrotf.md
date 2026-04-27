---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/idrotf
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
aliases:
- "Dzaan's Simulacrum"
---
# Dzaan's Simulacrum
*Source: Icewind Dale: Rime of the Frostmaiden p. 270*  

Unbeknownst to his executioners, Dzaan had used a spell scroll of simulacrum to create a copy of himself. This simulacrum dwells in the sunken Netherese spire, waiting for its creator to return.

The simulacrum, which looks and acts like Dzaan, has half of Dzaan's hit points and can't regain expended spell slots. It has wasted its 3rd-level spell slots trying to reach Dzaan with [sending](z_CLI/spells/sending-xphb.md) spells, to no avail, and has expended other spell slots to help it survive the perils of the spire. It uses its remaining spell slots sparingly.

The sunken Netherese tower contains a special room that can transform the simulacrum into a real person—or any magical illusion into the real thing, for that matter. If this change occurs, the simulacrum effectively becomes a clone of Dzaan, authentic in every way.

```ad-statblock
title: Dzaan's Simulacrum
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Dzaan%27s%20Simulacrum.webp#token)
*Medium construct, Lawful Evil*

- **Armor Class** 10
- **Hit Points** 24 (`9d8 + 9`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|11 (+0)|12 (+1)|16 (+3)|13 (+1)|15 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** Intelligence +5, Wisdom +3
- **Skills** [Arcana](z_CLI/rules/skills.md#Arcana) +5, [Deception](z_CLI/rules/skills.md#Deception) +4, [History](z_CLI/rules/skills.md#History) +5
- **Senses** passive Perception 11
- **Languages** Abyssal, Common, Giant, Infernal
- **Challenge** 1

## Traits

***Spellcasting.*** The simulacrum is a 9th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 13, `+5` to hit with spell attacks). It has the following wizard spells prepared:

**Cantrips (at will):** [acid splash](z_CLI/spells/acid-splash-xphb.md)*, [light](z_CLI/spells/light-xphb.md), [minor illusion](z_CLI/spells/minor-illusion-xphb.md), [shocking grasp](z_CLI/spells/shocking-grasp-xphb.md)*

**1st level (2 slots):** [detect magic](z_CLI/spells/detect-magic-xphb.md), [disguise self](z_CLI/spells/disguise-self-xphb.md), [magic missile](z_CLI/spells/magic-missile-xphb.md)*

**2nd level (2 slots):** [invisibility](z_CLI/spells/invisibility-xphb.md), [levitate](z_CLI/spells/levitate-xphb.md), [phantasmal force](z_CLI/spells/phantasmal-force-xphb.md)

*See "Actions" below.

## Actions

***Shocking Grasp (Cantrip).*** *Melee Spell Attack:* `+5` to hit, reach 5 ft., one creature (the attack roll has advantage if the target is wearing armor made of metal). *Hit:* 9 (`2d8`) lightning damage, and the target can't take reactions until the start of its next turn.

***Acid Splash (Cantrip).*** The simulacrum hurls a bubble of acid at one creature it can see within 60 feet of it, or at two such creatures that are within 5 feet of each other. A target must succeed on a DC 13 Dexterity saving throw or take 7 (`2d6`) acid damage.

***Magic Missile (1st-Level Spell; Requires a Spell Slot).*** The simulacrum creates three darts of magical force. Each dart unerringly strikes one creature the simulacrum can see within 120 feet of it, dealing 3 (`1d4 + 1`) force damage. If the simulacrum casts this spell using a 2nd-level spell slot, it creates one more dart.
```
^statblock