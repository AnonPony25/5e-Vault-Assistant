---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/toa
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity/shapechanger
- ttrpg-cli/monster/type/monstrosity/yuan-ti
aliases:
- "Fenthaza"
---
# Fenthaza
*Source: Tomb of Annihilation p. 113*  

```ad-statblock
title: Fenthaza
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Fenthaza.webp#token)
*Medium monstrosity (shapechanger, yuan-ti), Neutral Evil*

- **Armor Class** 14 (natural armor)
- **Hit Points** 71 (`13d8 + 13`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|14 (+2)|13 (+1)|14 (+2)|12 (+1)|16 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +3, Charisma +5
- **Skills** [Deception](z_CLI/rules/skills.md#Deception) +5, [Stealth](z_CLI/rules/skills.md#Stealth) +4
- **Senses** [darkvision](z_CLI/rules/senses.md#Darkvision) 120 ft. (penetrates magical darkness), passive Perception 11
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](z_CLI/rules/conditions.md#Poisoned)
- **Gear** [scimitar](z_CLI/items/scimitar-xphb.md)
- **Languages** Abyssal, Common, Draconic
- **Challenge** 4

## Traits

***Spellcasting (Yuan-ti Form Only).*** Fenthaza is a 6th-level spellcaster. Its spellcasting ability is Charisma (spell save DC 13, `+5` to hit with spell attacks). It regains its expended spell slots when it finishes a short or long rest. It knows the following warlock spells:

**Cantrips (at will):** [chill touch](z_CLI/spells/chill-touch-xphb.md), [eldritch blast](z_CLI/spells/eldritch-blast-xphb.md) (range 300 ft., +3 bonus to each damage roll), [mage hand](z_CLI/spells/mage-hand-xphb.md), [message](z_CLI/spells/message-xphb.md), [poison spray](z_CLI/spells/poison-spray-xphb.md), [prestidigitation](z_CLI/spells/prestidigitation-xphb.md)

**1st-3rd level (2 slots):** [arms of Hadar](z_CLI/spells/arms-of-hadar-xphb.md), [darkness](z_CLI/spells/darkness-xphb.md), [fear](z_CLI/spells/fear-xphb.md), [hex](z_CLI/spells/hex-xphb.md), [hold person](z_CLI/spells/hold-person-xphb.md), [hunger of Hadar](z_CLI/spells/hunger-of-hadar-xphb.md), [witch bolt](z_CLI/spells/witch-bolt-xphb.md)

***Innate Spellcasting (Yuan-ti Form Only).*** Fenthaza's innate spellcasting ability is Charisma (spell save DC 13). Fenthaza can innately cast the following spells, requiring no material components:

**At will:** [animal friendship](z_CLI/spells/animal-friendship-xphb.md) (snakes only)

**3/day:** [suggestion](z_CLI/spells/suggestion-xphb.md)

***Shapechanger.*** Fenthaza can use its action to polymorph into a Medium snake or back into its true form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. If it dies, it stays in its current form.

***Death Fangs (2/Day).*** The first time Fenthaza hits with a melee attack on its turn, it can deal an extra 16 (`3d10`) necrotic damage to the target.

***Magic Resistance.*** Fenthaza has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack (Yuan-ti Form Only).*** Fenthaza makes one constrict attack and one scimitar attack.

***Constrict.*** *Melee Weapon Attack:* `+5` to hit, reach 10 ft., one target. *Hit:* 10 (`2d6 + 3`) bludgeoning damage, and the target is [grappled](z_CLI/rules/conditions.md#Grappled) (escape DC 14) if it is a Large or smaller creature. Until this grapple ends, the target is [restrained](z_CLI/rules/conditions.md#Restrained), and Fenthaza can't constrict another target.

***Scimitar (Yuan-ti Form Only).*** *Melee Weapon Attack:* `+5` to hit, reach 5 ft., one target. *Hit:* 6 (`1d6 + 3`) slashing damage.

***Invoke Nightmare (Recharges after a Short or Long Rest).*** Fenthaza taps into the nightmares of a creature it can see within 60 feet of it and creates an illusory, immobile manifestation of the creature's deepest fears, visible only to that creature. The target must make a DC 13 Intelligence saving throw. On a failed save, the target takes 11 (`2d10`) psychic damage and is [frightened](z_CLI/rules/conditions.md#Frightened) of the manifestation, believing it to be real. Fenthaza must concentrate to maintain the illusion (as if [concentrating](z_CLI/rules/conditions.md#Concentration) on a spell), which lasts for up to 1 minute and can't be harmed. The target can repeat the saving throw at the end of each of its turns, ending the illusion on a success, or taking 11 (`2d10`) psychic damage on a failure.
```
^statblock