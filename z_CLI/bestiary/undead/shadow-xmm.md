---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/shadowfell
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
aliases:
- "Shadow"
---
# Shadow
*Source: Monster Manual (2024) p. 272. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Shadow

*Disembodied, Life-Drinking Shade*

- **Habitat.** Planar (Shadowfell), Underdark, Urban  
- **Treasure.** None  

Shadows are incorporeal Undead that feed on life. They resent the living for possessing the potential and vitality lost to them.

Shadows lurk in dark, lonely places, typically sites that were meaningful to them in life or cursed places with ties to death, sinister magic, or the Shadowfell. Their victims rise as new shadows and prey on the living.

Shadows might resemble the silhouettes of who they were in life or take on more menacing forms. Roll on or choose a result from the Shadow Shapes table to inspire a shadow's form and haunting.

**Shadow Shapes**

| dice: 1d6 | The Shadow Appears As... |
|-----------|--------------------------|
| 1 | A distorted stalker that lurks in the woods. |
| 2 | A fiend that dwells near a wicked ritual site. |
| 3 | Grasping hands that haunt a miser's home. |
| 4 | A grim storybook character that follows those who speak its name. |
| 5 | Its target, acting in eerie pantomime. |
| 6 | An ominous priest that haunts a defiled site. |
^shadow-shapes

```ad-statblock
title: Shadow
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Shadow.webp#token)
*Medium undead, Chaotic Evil*

- **Armor Class** 12
- **Hit Points** 27 (`5d8 + 5`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|14 (+2)|13 (+1)| 6 (-2)|10 (+0)| 8 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** [Stealth](z_CLI/rules/skills.md#Stealth) +6
- **Senses** [Darkvision](z_CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 10
- **Damage Vulnerabilities** radiant
- **Damage Resistances** acid, cold, fire, lightning, thunder
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [exhaustion](z_CLI/rules/conditions.md#Exhaustion), [frightened](z_CLI/rules/conditions.md#Frightened), [grappled](z_CLI/rules/conditions.md#Grappled), [paralyzed](z_CLI/rules/conditions.md#Paralyzed), [petrified](z_CLI/rules/conditions.md#Petrified), [poisoned](z_CLI/rules/conditions.md#Poisoned), [prone](z_CLI/rules/conditions.md#Prone), [restrained](z_CLI/rules/conditions.md#Restrained), [unconscious](z_CLI/rules/conditions.md#Unconscious)
- **Languages** —
- **Challenge** 1/2

## Traits

***Amorphous.*** The shadow can move through a space as narrow as 1 inch without expending extra movement to do so.

***Sunlight Weakness.*** While in sunlight, the shadow has [Disadvantage](z_CLI/rules/variant-rules/disadvantage-xphb.md) on [D20 Tests](z_CLI/rules/variant-rules/d20-test-xphb.md).

## Actions

***Draining Swipe.*** *Melee Attack Roll:* `+4`, reach 5 ft. *Hit:* 5 (`1d6 + 2`) Necrotic damage, and the target's Strength score decreases by `1d4`. The target dies if this reduces that score to 0. If a Humanoid is slain by this attack, a Shadow rises from the corpse `1d4` hours later.

## Bonus Actions

***Shadow Stealth.*** While in [Dim Light](z_CLI/rules/variant-rules/dim-light-xphb.md) or [Darkness](z_CLI/rules/variant-rules/darkness-xphb.md), the shadow takes the [Hide](z_CLI/rules/actions.md#Hide) action.
```
^statblock

## Environment

planar, shadowfell, underdark, urban