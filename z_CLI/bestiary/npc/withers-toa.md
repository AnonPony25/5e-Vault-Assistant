---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/toa
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
aliases:
- "Withers"
---
# Withers
*Source: Tomb of Annihilation p. 145*  

Before he was turned into an undead creature, Withers was an Omuan engineer named Gorra. Like all of Omu's citizens, Gorra was enslaved and put to work constructing the tomb. When Acererak sacrificed his workers to their own dungeon, Gorra's traps performed the best.

```ad-statblock
title: Withers
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Withers.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 14 ([studded leather](z_CLI/items/studded-leather-armor-xphb.md))
- **Hit Points** 45 (`6d8 + 18`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|14 (+2)|16 (+3)|16 (+3)|13 (+1)|15 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** [Perception](z_CLI/rules/skills.md#Perception) +3, [Stealth](z_CLI/rules/skills.md#Stealth) +4
- **Senses** [darkvision](z_CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 13
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](z_CLI/rules/conditions.md#Exhaustion), [poisoned](z_CLI/rules/conditions.md#Poisoned)
- **Gear** [longsword](z_CLI/items/longsword-xphb.md)
- **Languages** the languages he knew in life
- **Challenge** 4

## Traits

***Spellcasting.*** Withers is a 9th-level spellcaster. His spellcasting ability is Intelligence (spell save DC 13, `+5` to hit with spell attacks). Withers has the following wizard spells prepared:

**Cantrips (at will):** [acid splash](z_CLI/spells/acid-splash-xphb.md), [mage hand](z_CLI/spells/mage-hand-xphb.md), [minor illusion](z_CLI/spells/minor-illusion-xphb.md), [prestidigitation](z_CLI/spells/prestidigitation-xphb.md)

**1st level (4 slots):** [detect magic](z_CLI/spells/detect-magic-xphb.md), [expeditious retreat](z_CLI/spells/expeditious-retreat-xphb.md), [feather fall](z_CLI/spells/feather-fall-xphb.md), [thunderwave](z_CLI/spells/thunderwave-xphb.md)

**2nd level (4 slots):** [darkness](z_CLI/spells/darkness-xphb.md), [hold person](z_CLI/spells/hold-person-xphb.md), [rope trick](z_CLI/spells/rope-trick-xphb.md)

**3rd level (3 slots):** [dispel magic](z_CLI/spells/dispel-magic-xphb.md), [lightning bolt](z_CLI/spells/lightning-bolt-xphb.md)

**4th level (3 slots):** [blight](z_CLI/spells/blight-xphb.md), [wall of fire](z_CLI/spells/wall-of-fire-xphb.md)

**5th level (1 slots):** [telekinesis](z_CLI/spells/telekinesis-xphb.md)

***Special Equipment.*** Withers carries the [amulet of the black skull](z_CLI/items/amulet-of-the-black-skull-toa.md).

***Sunlight Sensitivity.*** While in sunlight, Withers has disadvantage on attack rolls, as well as on Wisdom ([Perception](z_CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Multiattack.*** Withers makes two longsword attacks. He can use his Life Drain in place of one longsword attack.

***Life Drain.*** *Melee Weapon Attack:* `+4` to hit, reach 5 ft., one creature. *Hit:* 5 (`1d6 + 2`) necrotic damage. The target must succeed on a DC 13 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.

A humanoid slain by this attack rises 24 hours later as a zombie under the Withers's control, unless the humanoid is restored to life or its body is destroyed. Withers can have no more than twelve zombies under its control at one time.

***Longsword.*** *Melee Weapon Attack:* `+4` to hit, reach 5 ft., one target. *Hit:* 6 (`1d8 + 2`) slashing damage, or 7 (`1d10 + 2`) slashing damage if used with two hands.
```
^statblock