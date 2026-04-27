---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/cleric
aliases:
- "War Priest"
---
# War Priest
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 254*  

War priests worship deities of war, protection, and strategy. They plan tactics, lead soldiers into battle, confront enemy spellcasters, and tend to casualties. A war priest might command an army or serve as the right hand of a [warlord](z_CLI/bestiary/humanoid/warlord-mpmm.md) (appears in "this book") on the battlefield.

War priests typically adorn themselves with a symbol of their faith. You can roll on the War Priest Holy Symbols table below, or choose one that fits your campaign.

**War Priest Holy Symbols**

| dice: d8 | Holy Symbol |
|----------|-------------|
| 1 | Vial of iridescent liquid |
| 2 | Hilt of a broken sword |
| 3 | Piece of stained glass from a shrine |
| 4 | Clay figurine of a [ki-rin](z_CLI/bestiary/celestial/ki-rin-mpmm.md) or another Celestial |
| 5 | [Torch](z_CLI/items/torch-xphb.md) carved so that a hand appears to be holding the flame |
| 6 | Circlet of woven reeds |
| 7 | Scrimshawed bone |
| 8 | Vessel such as a cup, a [jug](z_CLI/items/jug-xphb.md), an urn, or an amphora |
^war-priest-holy-symbols

```ad-statblock
title: War Priest
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/War%20Priest.webp#token)
*Medium humanoid (cleric), Any alignment*

- **Armor Class** 18 ([plate](z_CLI/items/plate-armor-xphb.md))
- **Hit Points** 117 (`18d8 + 36`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|10 (+0)|14 (+2)|11 (+0)|17 (+3)|13 (+1)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +6, Wisdom +7
- **Skills** [Intimidation](z_CLI/rules/skills.md#Intimidation) +5, [Religion](z_CLI/rules/skills.md#Religion) +4
- **Senses** passive Perception 13
- **Gear** [maul](z_CLI/items/maul-xphb.md)
- **Languages** any two languages
- **Challenge** 9

## Actions

***Multiattack.*** The war priest makes two Maul attacks, and it uses Holy Fire.

***Maul.*** *Melee Weapon Attack:* `+7` to hit, reach 5 ft., one target. *Hit:* 10 (`2d6 + 3`) bludgeoning damage  plus *Hit:* 10 (`3d6`) radiant damage.

***Holy Fire.*** The war priest targets one creature it can see within 60 feet of it. The target must make a DC 15 Wisdom saving throw. On a failed save, the target takes 12 (`2d8 + 3`) radiant damage, and it is [blinded](z_CLI/rules/conditions.md#Blinded) until the start of the war priest's next turn. On a successful save, the target takes half as much damage and isn't [blinded](z_CLI/rules/conditions.md#Blinded).

***Spellcasting.*** The war priest casts one of the following spells, using Wisdom as the spellcasting ability (spell save DC 15):

**At will:** [light](z_CLI/spells/light-xphb.md), [spare the dying](z_CLI/spells/spare-the-dying-xphb.md), [thaumaturgy](z_CLI/spells/thaumaturgy-xphb.md)

**1/day each:** [banishment](z_CLI/spells/banishment-xphb.md), [command](z_CLI/spells/command-xphb.md), [dispel magic](z_CLI/spells/dispel-magic-xphb.md), [flame strike](z_CLI/spells/flame-strike-xphb.md), [guardian of faith](z_CLI/spells/guardian-of-faith-xphb.md), [hold person](z_CLI/spells/hold-person-xphb.md), [lesser restoration](z_CLI/spells/lesser-restoration-xphb.md), [revivify](z_CLI/spells/revivify-xphb.md)

## Bonus Actions

***Healing Light (Recharge 4-6).*** The war priest or one creature of its choice within 60 feet of it regains 12 (`2d8 + 3`) hit points.
```
^statblock

## Environment

desert, urban