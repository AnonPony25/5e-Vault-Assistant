---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/vrgr
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
aliases:
- "Relentless Slasher"
---
# Relentless Slasher
*Source: Van Richten's Guide to Ravenloft p. 242*  

A relentless slasher conducts its bloody work in silence then vanishes into shadow and infamy. Fixated on a specific individual or type of victim, it pursues its target with single-minded obsession.

Relentless killers are hateful, revenge-obsessed creatures that enter into pacts with fiends or other nefarious entities. Their bargains transform them into vicious butchers that exist only to indulge their endless bloodlust. While some who become relentless killers began life as innocents, any semblance of who they were is washed away in a tide of gore and rage. These killers' grisly work swiftly becomes the stuff of legends, striking fear into innocents across lands and over ages.

## Creating a Relentless Killer

Relentless killers come into being and undertake their terrifying sprees for a spectrum of reasons. When creating a relentless killer, consider what circumstances led to their transformation and signature methods. Roll or choose options from the Relentless Origins and Relentless Methods tables when creating your own, unique monstrous slayers.

**Relentless Origins**

| dice: d6 | Origin |
|----------|--------|
| 1 | It was left for dead and granted new life to seek revenge. |
| 2 | It was turned into a weapon of vengeance by a family member's bargain with sinister forces. |
| 3 | It was marked by a fiend before its birth, and its wicked nature emerged over time. |
| 4 | A wicked place or magic relic seeped into its being, turning it into a monster. |
| 5 | The killer used its body to contain an evil entity. |
| 6 | The killer appears to be an ordinary person who doesn't realize it turns into a killer when enraged. |
^relentless-origins

**Relentless Methods**

| dice: d8 | Method |
|----------|--------|
| 1 | Artist. The killer turns its victims into works of art, perhaps creating grisly tableaus or using their blood in the forging of new weapons. |
| 2 | Author. The killer leaves messages, poems, song lyrics, or parts of its creative masterpiece at the scenes of its crimes. |
| 3 | Avatar. The killer sacrifices its victims, believing it's a manifestation of a deity or force beyond morality. |
| 4 | Doctor. The killer dissects victims or harvests their organs for the sake of medical understanding. |
| 5 | Mask. The killer wears a distinctive disguise, its visage becoming a symbol of its crimes. |
| 6 | Penitent. The killer can't help itself from committing crimes and seeks help to thwart its own continuing violence. |
| 7 | Ritualist. The killer always attacks the same type of person in the same type of place in the same way. |
| 8 | Trophy Taker. The killer reliably collects something from its victims, hoarding them as trophies. |
^relentless-methods

## Statblock

```ad-statblock
title: Relentless Slasher
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VRGR/Relentless%20Slasher.webp#token)
*Medium fiend, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 84 (`13d8 + 26`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|18 (+4)|14 (+2)|14 (+2)|15 (+2)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +4, Dexterity +7, Constitution +5, Wisdom +5
- **Skills** [Athletics](z_CLI/rules/skills.md#Athletics) +7, [Perception](z_CLI/rules/skills.md#Perception) +5, [Survival](z_CLI/rules/skills.md#Survival) +5
- **Senses** [darkvision](z_CLI/rules/senses.md#Darkvision) 120 ft., passive Perception 15
- **Condition Immunities** [charmed](z_CLI/rules/conditions.md#Charmed), [frightened](z_CLI/rules/conditions.md#Frightened)
- **Languages** understands all languages but can't speak
- **Challenge** 8

## Traits

***Legendary Resistance (1/Day).*** If the slasher fails a saving throw, it can choose to succeed instead.

***Shrouded Presence.*** The slasher is immune to any effect that would sense its emotions or read its thoughts, and it can't be detected by abilities that sense Fiends.

## Actions

***Multiattack.*** The slasher makes two Slasher's Knife attacks.

***Slasher's Knife.*** *Melee  or Ranged Weapon Attack:* `+7` to hit, reach 5 ft. or range 30/60 ft., one target. *Hit:* 6 (`1d4 + 4`) slashing damage plus 21 (`6d6`) necrotic damage. If the target is a creature, it suffers a lingering wound that causes it to take 7 (`2d6`) necrotic damage at the start of each of its turns. Each time the slasher hits the wounded target with this attack, the damage dealt by the wound increases by 3 (`1d6`). The wound ends if the target regains hit points or if a creature uses an action to stanch the wound, which requires a successful DC 15 Wisdom ([Medicine](z_CLI/rules/skills.md#Medicine)) check.

## Legendary Actions

Legendary Action Uses: 3. Immediately after another creature's turn, the relentless slasher can expend a use to take one of the following actions. The relentless slasher regains all expended uses at the start of each of its turns.

***Slice.*** *Melee  or Ranged Weapon Attack:* `+7` to hit, reach 5 ft. or range 30/60 ft., one target. *Hit:* 7 (`1d6 + 4`) slashing damage.

***Vanishing Strike (Costs 3 Actions).*** The slasher makes one Slasher's Knife attack. After the attack hits or misses, the slasher can teleport up to 30 feet to an unoccupied space it can see.
```
^statblock