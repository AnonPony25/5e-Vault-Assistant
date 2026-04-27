---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/vrgr
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend
aliases:
- "Relentless Juggernaut"
---
# Relentless Juggernaut
*Source: Van Richten's Guide to Ravenloft p. 243*  

Relentless juggernauts are massive brutes that thirst for carnage. Their presence twists the world around them, allowing them to create weapons with which they can slaughter prey. Sharp iron fences, crushing stalagmites and blades of glass all conveniently appear in order to aid a juggernaut's brutality. Every juggernaut considers a certain area its territory and visits destruction upon all trespassers.

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
title: Relentless Juggernaut
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VRGR/Relentless%20Juggernaut.webp#token)
*Large fiend, Unaligned*

- **Armor Class** 17 (natural armor)
- **Hit Points** 161 (`14d10 + 84`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|12 (+1)|22 (+6)| 8 (-1)|15 (+2)|16 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +5, Wisdom +6, Charisma +7
- **Skills** [Perception](z_CLI/rules/skills.md#Perception) +6, [Survival](z_CLI/rules/skills.md#Survival) +6
- **Senses** [darkvision](z_CLI/rules/senses.md#Darkvision) 120 ft., passive Perception 16
- **Condition Immunities** [charmed](z_CLI/rules/conditions.md#Charmed), [exhaustion](z_CLI/rules/conditions.md#Exhaustion), [frightened](z_CLI/rules/conditions.md#Frightened)
- **Languages** understands all languages but can't speak
- **Challenge** 12

## Traits

***Legendary Resistance (3/Day).*** If the juggernaut fails a saving throw, it can choose to succeed instead.

***Regeneration.*** The juggernaut regains 20 hit points at the start of its turn. If the juggernaut takes radiant damage, this trait doesn't function at the start of its next turn. The juggernaut dies only if it starts its turn with 0 hit points and doesn't regenerate.

***Unusual Nature.*** The juggernaut doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The juggernaut makes two attacks. It can replace one attack with Deadly Shaping if it is ready.

***Executioner's Pick.*** *Melee Weapon Attack:* `+10` to hit, reach 5 ft., one target. *Hit:* 17 (`2d10 + 6`) piercing damage, and if the target is a creature, its speed is reduced by 10 feet until the start of the juggernaut's next turn.

***Fist.*** *Melee Weapon Attack:* `+10` to hit, reach 5 ft., one target. *Hit:* 11 (`1d10 + 6`) bludgeoning damage, and if the target is a Large or smaller creature, it must succeed on a DC 18 Strength saving throw or be knocked [prone](z_CLI/rules/conditions.md#Prone).

***Deadly Shaping (Recharge 5-6).*** The juggernaut magically shapes a feature of its surroundings into a deadly implement. A creature the juggernaut can see within 60 feet of it must make a DC 18 Dexterity saving throw. If the saving throw fails, the targeted creature is struck by one of the following (juggernaut's choice):

***Flying Stone.*** The target takes 22 (`5d8`) bludgeoning damage and is [incapacitated](z_CLI/rules/conditions.md#Incapacitated) until the start of the juggernaut's next turn, and the implement vanishes.

***Scything Shrapnel.*** The target takes 14 (`4d6`) slashing damage, and the implement vanishes. At the start of each of its turns, the target takes 10 (`3d6`) necrotic damage from the wound left by the shrapnel. The wound ends if the target regains any hit points or if a creature uses an action to stanch the wound, which requires a successful DC 15 Wisdom ([Medicine](z_CLI/rules/skills.md#Medicine)) check.

## Legendary Actions

Legendary Action Uses: 3. Immediately after another creature's turn, the relentless juggernaut can expend a use to take one of the following actions. The relentless juggernaut regains all expended uses at the start of each of its turns.

***Implacable Advance.*** The juggernaut moves up to its speed, ignoring difficult terrain. Any object in its path takes 55 (`10d10`) bludgeoning damage if it isn't being worn or carried.

***Rapid Shaping (Costs 3 Actions).*** The juggernaut recharges Deadly Shaping and uses it.
```
^statblock