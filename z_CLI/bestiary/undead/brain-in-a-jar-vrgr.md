---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/vrgr
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/undead
aliases:
- "Brain in a Jar"
---
# Brain in a Jar
*Source: Van Richten's Guide to Ravenloft p. 278, Icewind Dale: Rime of the Frostmaiden p. 279*  

Through an eldritch ritual combining alchemy, necromancy, and grim surgical precision, the brain of a mortal being (willing or unwilling) is encased in a glass jar filled with preserving fluids and the liquefied goop of their body's flesh. The transformation renders the brain immortal and imbues it with psionic power, so that it can spend eternity plotting and executing its desires.

A brain in a jar can speak without vocal cords, psionically projecting its disembodied voice outward for all to hear. It enjoys conversation so much that it is prone to talking for hours on end, sometimes to itself if there are no others with whom it can speak. It also likes to think out loud and reflect on the events and decisions that led to its great transformation.

Being divorced from one's body can tax the mind, and the longer a brain in a jar exists, the more likely some form of insanity will take hold of it. A brain in a jar is particularly susceptible to dementia, schizophrenia, and paranoia.

## Immortal Vessels

The brain floats in a jar of solution, pulsating as it reacts to its surroundings. Some brains have been known to thump against the walls of their containers when excited or vexed. A jar's metal casing might be rusty but serviceable, or an elegantly wrought masterwork, depending on its creator. A brain in a jar weighs roughly 125 pounds.

## Statblock

```ad-statblock
title: Brain in a Jar
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VRGR/Brain%20in%20a%20Jar.webp#token)
*Small undead, Any alignment*

- **Armor Class** 11 (natural armor)
- **Hit Points** 55 (`10d6 + 20`)
- **Speed** 0 ft., fly 10 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 (-5)| 3 (-4)|15 (+2)|19 (+4)|10 (+0)|15 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** Intelligence +6, Charisma +4
- **Skills** ⏤
- **Senses** [blindsight](z_CLI/rules/senses.md#Blindsight) 120 ft. (blind beyond this radius); see also "detect sentience" below, passive Perception 10
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](z_CLI/rules/conditions.md#Exhaustion), [paralyzed](z_CLI/rules/conditions.md#Paralyzed), [poisoned](z_CLI/rules/conditions.md#Poisoned), [prone](z_CLI/rules/conditions.md#Prone)
- **Languages** the languages it knew in life
- **Challenge** 3

## Traits

***Innate Spellcasting (Psionics).*** The brain's innate spellcasting ability is Intelligence (spell save DC 14, `+6` to hit with spell attacks). It can innately cast the following spells, requiring no components:

**At will:** [chill touch](z_CLI/spells/chill-touch-xphb.md) (see "Actions" below), [detect thoughts](z_CLI/spells/detect-thoughts-xphb.md), [mage hand](z_CLI/spells/mage-hand-xphb.md), [zone of truth](z_CLI/spells/zone-of-truth-xphb.md)

**3/day each:** [charm person](z_CLI/spells/charm-person-xphb.md), [hold person](z_CLI/spells/hold-person-xphb.md)

**1/day each:** [compulsion](z_CLI/spells/compulsion-xphb.md), [hold monster](z_CLI/spells/hold-monster-xphb.md), [sleep](z_CLI/spells/sleep-xphb.md) (3rd-level version), [Tasha's hideous laughter](z_CLI/spells/tashas-hideous-laughter-xphb.md)

***Detect Sentience.*** The brain can sense the presence and location of any creature within 300 feet of it that has an Intelligence of 3 or higher, regardless of interposing barriers, unless the creature is protected by a [mind blank](z_CLI/spells/mind-blank-xphb.md) spell.

***Magic Resistance.*** The brain has advantage on saving throws against spells and other magic effects.

***Unusual Nature.*** The brain doesn't require air, food, drink, or sleep.

## Actions

***Chill Touch (Cantrip).*** *Ranged Spell Attack:* `+6` to hit, range 120 ft., one creature. *Hit:* 13 (`3d8`) necrotic damage, and the target can't regain hit points until the start of the brain's next turn. If the target is undead, it also has disadvantage on attack rolls against the brain until the end of the brain's next turn.

***Mind Blast (Recharge 5-6).*** The brain magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a DC 14 Intelligence saving throw or take 17 (`3d8 + 4`) psychic damage and be [stunned](z_CLI/rules/conditions.md#Stunned) for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock