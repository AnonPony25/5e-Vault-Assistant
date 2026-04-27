---
obsidianUIMode: preview
cssclasses:
- json5e-note
tags:
- ttrpg-cli/compendium/src/5e/xphb
aliases:
- "Chapter 7: Spells"
---
# Chapter 7: Spells
*Source: Player's Handbook (2024), p. 235* 

![Archmages of Greyhawk—Jallarzi, Mordenkainen, and Bigby—prepare their magic as they open a gate to another plane](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/book/XPHB/181-08-001.jallarzi-mordenkainen-bigby.webp#center)

This chapter gives rules for casting spells. It also includes "descriptions" of common spells in the worlds of Dungeons & Dragons. Those spells are used by many class features, magic items, and monsters.

## Gaining Spells

Before you can cast a spell, you must have the spell prepared in your mind or have access to the spell from a magic item, such as a [Spell Scroll](z_CLI/items/spell-scroll-xdmg.md). Your features specify which spells you have access to, if any; whether you always have certain spells prepared; and whether you can change the list of spells you have prepared.

### Preparing Spells

If you have a list of level 1+ spells you prepare, your spellcasting feature specifies when you can change the list and the number of spells you can change, as summarized in the Spell Preparation by Class table.

![Preparing Spells; Spell Preparation by Class](z_CLI/tables/preparing-spells-spell-preparation-by-class-xphb.md)

Most spellcasting monsters don't change their lists of prepared spells, but the DM is free to alter them.

### Always-Prepared Spells

Certain features might give you a spell that you always have prepared. If you also have a list of prepared spells that you can change, a spell that you always have prepared doesn't count against the number of spells on that list.

> [!note] Casting in Armor
> 
> You must have training with any armor you are wearing to cast spells while wearing it. You are otherwise too hampered by the armor for spellcasting.
^casting-in-armor

## Casting Spells

Each "spell description" has a series of entries that provide the details needed to cast the spell. The following sections explain each of those entries, which follow a spell's name.

### Spell Level

Every spell has a level from 0 to 9, which is indicated in a spell's description. A spell's level is an indicator of how powerful it is. Cantrips—simple spells that can be cast almost by rote—are level 0. The rules for each spellcasting class say when its members gain access to spells of certain levels.

#### Spell Slots

Spellcasting is taxing, so a spellcaster can cast only a limited number of level 1+ spells before resting. Spell slots are the main way a spellcaster's magical potential is represented. Each spellcasting class gives its members a limited number of spell slots of certain spell levels. For example, a level 3 Wizard has four level 1 spell slots and two level 2 slots.

When you cast a spell, you expend a slot of that spell's level or higher, effectively "filling" a slot with the spell. Imagine a spell slot is a groove of a certain size—small for a level 1 slot and larger for a higher-level spell. A level 1 spell fits into a slot of any size, but a level 2 spell fits only into a slot that's at least level 2. So when a level 3 Wizard casts [Magic Missile](z_CLI/spells/magic-missile-xphb.md), a level 1 spell, that Wizard spends one of four level 1 slots and has three remaining.

Finishing a [Long Rest](z_CLI/rules/variant-rules/long-rest-xphb.md) restores any expended spell slots.

#### Casting without Slots

There are several ways to cast a spell without expending a spell slot:

- **Cantrips.** A cantrip is cast without a spell slot.  
- **Rituals.** Certain spells have the Ritual tag in the Casting Time entry. Such a spell can be cast following the normal rules for spellcasting, or it can be cast as a Ritual. The Ritual version of a spell takes 10 minutes longer to cast than normal, but it doesn't expend a spell slot. To cast a spell as a Ritual, a spellcaster must have it prepared.  
- **Special Abilities.** Some characters and monsters have special abilities that allow them to cast specific spells without a spell slot. This casting is usually limited in another way, such as being able to cast the spell a limited number of times per day.  
- **Magic Items.** [Spell Scrolls](z_CLI/items/spell-scroll-xdmg.md) and some other magic items contain spells that can be cast without a spell slot. The description of such an item specifies how many times a spell can be cast from it.  

#### Using a Higher-Level Spell Slot

When a spellcaster casts a spell using a slot that is of a higher level than the spell, the spell takes on the higher level for that casting. For instance, if a Wizard casts [Magic Missile](z_CLI/spells/magic-missile-xphb.md) using a level 2 slot, that *Magic Missile* is level 2. Effectively, the spell expands to fill the slot it is put into.

Some spells, such as [Magic Missile](z_CLI/spells/magic-missile-xphb.md) and [Cure Wounds](z_CLI/spells/cure-wounds-xphb.md), have more powerful effects when cast at a higher level, as detailed in a spell's description.

### School of Magic

Each spell belongs to a school of magic. The schools are listed in the Schools of Magic table. These categories help describe spells but have no rules of their own, although some other rules refer to them.

![School of Magic; Schools of Magic](z_CLI/tables/school-of-magic-schools-of-magic-xphb.md)

### Class Spell Lists

If a spell is on a class's spell list, the class's name appears in parentheses after the spell's school of magic. Some features add a spell to a character's spell list even if the character isn't a member of a class in the parentheses.

### Casting Time

Most spells require the [Magic](z_CLI/rules/actions.md#Magic) action to cast, but some spells require a Bonus Action, a Reaction, or 1 minute or more. A spell's Casting Time entry specifies which of those is required.

#### One Spell with a Spell Slot per Turn

On a turn, you can expend only one spell slot to cast a spell. This rule means you can't, for example, cast a spell with a spell slot using the [Magic](z_CLI/rules/actions.md#Magic) action and another one using a Bonus Action on the same turn.

#### Reaction and Bonus Action Triggers

A spell that has a casting time of a Reaction is cast in response to a trigger that is defined in the spell's Casting Time entry. Some spells that have a casting time of a Bonus Action are also cast in response to a trigger defined in the spell.

#### Longer Casting Times

Certain spells—including a spell cast as a [Ritual](z_CLI/rules/variant-rules/ritual-xphb.md)—require more time to cast: minutes or even hours. While you cast a spell with a casting time of 1 minute or more, you must take the [Magic](z_CLI/rules/actions.md#Magic) action on each of your turns, and you must maintain [Concentration](z_CLI/rules/conditions.md#Concentration) while you do so. If your Concentration is broken, the spell fails, but you don't expend a spell slot. To cast the spell again, you must start over.

### Range

A spell's range indicates how far from the spellcaster the spell's effect can originate, and the spell's description specifies which part of the effect is limited by the range.

A range usually takes one of the following forms:

- **Distance.** The range is expressed in feet.  
- **Touch.** The spell's effect originates on something the spellcaster must touch, as defined in the spell.  
- **Self.** The spell is cast on the spellcaster or emanates from them, as specified in the spell.  

If a spell has movable effects, they aren't restricted by its range unless the spell's description says otherwise.

### Components

![An aasimar Wizard uses a crystal material component to focus the magic of Cone of Cold](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/book/XPHB/182-08-002.aasimar-wizard.webp#center)

A spell's components are physical requirements the spellcaster must meet to cast the spell. Each spell's description indicates whether it requires Verbal (V), Somatic (S), or Material (M) components. If the spellcaster can't provide one or more of a spell's components, the spellcaster can't cast the spell.

#### Verbal (V)

A Verbal component is the chanting of esoteric words that sound like nonsense to the uninitiated. The words must be uttered in a normal speaking voice. The words themselves aren't the source of the spell's power; rather, the particular combination of sounds, with specific pitch and resonance, sets the threads of magic in motion. Thus, a creature who is gagged or in an area of magical silence can't cast a spell with a Verbal component.

> [!note] Creating Verbal Components
> 
> If you'd like to say a spell's Verbal component, you may make up the words. However you make them, the goal is to create something that's easy to say and that doesn't mean anything in the real world. Consider this method: take the name of the spell, keep only one instance of each of its letters, and rearrange the remaining letters into words. For example, remove the second *l* from [Fireball](z_CLI/spells/fireball-xphb.md) and rearrange the remaining letters to create *Ber Fila* or *Fel Bira*.
^creating-verbal-components

#### Somatic (S)

A Somatic component is a forceful gesticulation or an intricate set of gestures. A spellcaster must use at least one of their hands to perform these movements.

#### Material (M)

A Material component is a particular material used in a spell's casting, as specified in parentheses in the Components entry. These materials aren't consumed by the spell unless the spell's description states otherwise. The spellcaster must have a hand free to access them, but it can be the same hand used to perform Somatic components, if any.

If a spell doesn't consume its materials and doesn't specify a cost for them, a spellcaster can use a [Component Pouch](z_CLI/items/component-pouch-xphb.md) (see "chapter 6") instead of providing the materials specified in the spell, or the spellcaster can substitute a [Spellcasting Focus](z_CLI/rules/variant-rules/spellcasting-focus-xphb.md) if the caster has a feature that allows that substitution. To use a Component Pouch, you must have a hand free to reach into it, and to use a [Spellcasting Focus](z_CLI/rules/variant-rules/spellcasting-focus-xphb.md), you must hold it unless its description says otherwise (see "chapter 6" for descriptions).

### Duration

A spell's duration is the length of time the spell persists after it is cast. A duration typically takes one of the following forms:

- **Concentration.** A duration that requires Concentration follows the [Concentration](z_CLI/rules/conditions.md#Concentration) rules.  
- **Instantaneous.** An instantaneous duration means the spell's magic appears only for a moment and then disappears.  
- **Time Span.** A duration that provides a time span specifies how long the spell lasts in rounds, minutes, hours, or the like. For example, a Duration entry might say "1 minute," meaning the spell ends after 1 minute has passed. While a time-span spell that you cast is ongoing, you can dismiss it (no action required) if you don't have the [Incapacitated](z_CLI/rules/conditions.md#Incapacitated) condition.  

### Effects

The effects of a spell are detailed after its duration entry. Those details present exactly what the spell does, which ignores mundane physical laws; any outcomes beyond those effects are under the DM's purview. Whatever the effects, they typically deal with targets, saving throws, attack rolls, or all three, each of which is detailed below.

#### Targets

A typical spell requires the caster to pick one or more targets to be affected by the spell's magic. A spell's description says whether the spell targets creatures, objects, or something else.

##### A Clear Path to the Target

To target something with a spell, a caster must have a clear path to it, so it can't be behind [Total Cover](z_CLI/rules/variant-rules/cover-xphb.md).

##### Targeting Yourself

If a spell targets a creature of your choice, you can choose yourself unless the creature must be [Hostile](z_CLI/rules/variant-rules/hostile-attitude-xphb.md) or specifically a creature other than you.

##### Areas of Effect

Some spells, such as [Thunderwave](z_CLI/spells/thunderwave-xphb.md), cover an area called an [area of effect](z_CLI/rules/variant-rules/area-of-effect-xphb.md), which is defined in the "rules glossary". The area determines what the spell targets. The description of a spell specifies whether it has an area of effect, which is typically one of these shapes: [Cone](z_CLI/rules/variant-rules/cone-area-of-effect-xphb.md), [Cube](z_CLI/rules/variant-rules/cube-area-of-effect-xphb.md), [Cylinder](z_CLI/rules/variant-rules/cylinder-area-of-effect-xphb.md), [Emanation](z_CLI/rules/variant-rules/emanation-area-of-effect-xphb.md), [Line](z_CLI/rules/variant-rules/line-area-of-effect-xphb.md), or [Sphere](z_CLI/rules/variant-rules/sphere-area-of-effect-xphb.md).

![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/book/XPHB/183-08-003.areas-of-effect.webp#center)

##### Awareness of Being Targeted

Unless a spell has a perceptible effect, a creature doesn't know it was targeted by the spell. An effect like lightning is obvious, but a more subtle effect, such as an attempt to read thoughts, goes unnoticed unless a spell's description says otherwise.

##### Invalid Targets

If you cast a spell on someone or something that can't be affected by it, nothing happens to that target, but if you used a spell slot to cast the spell, the slot is still expended.

If the spell normally has no effect on a target that succeeds on a saving throw, the invalid target appears to have succeeded on its saving throw, even though it didn't attempt one (giving no hint that the creature is an invalid target). Otherwise, you perceive that the spell did nothing to the target.

#### Saving Throws

Many spells specify that a target makes a saving throw to avoid some or all of a spell's effects. The spell specifies the ability that the target uses for the save and what happens on a success or failure. Here's how to calculate the DC for your spells:

<span class='abilityDc'>**Spell save DC**: Spellcasting + Proficiency Bonus</span>

#### Attack Rolls

Some spells require the caster to make an attack roll to determine whether the spell hits a target. Here's how to calculate the attack modifier for your spells:

<span class='abilityAttackMod'>**Spell attack modifier**: Spellcasting + Proficiency Bonus</span>

#### Combining Spell Effects

The effects of different spells add together while their durations overlap. In contrast, the effects of the same spell cast multiple times don't combine. Instead, the most potent effect—such as the highest bonus—from those castings applies while their durations overlap. The most recent effect applies if the castings are equally potent and their durations overlap. For example, if two Clerics cast [Bless](z_CLI/spells/bless-xphb.md) on the same target, that target gains the spell's benefit only once; the target doesn't receive two bonus dice. But if the durations of the spells overlap, the effect continues until the duration of the second *Bless* ends.

> [!note] Identifying an Ongoing Spell
> 
> You can try to identify a non-instantaneous spell by its observable effects if its duration is ongoing. To identify it, you must take the [Study](z_CLI/rules/actions.md#Study) action and succeed on a DC 15 Intelligence ([Arcana](z_CLI/rules/skills.md#Arcana)) check.
^identifying-an-ongoing-spell

## Spell Descriptions

The spells are presented in alphabetical order.

- [Acid Splash](z_CLI/spells/acid-splash-xphb.md)  
- [Aid](z_CLI/spells/aid-xphb.md)  
- [Alarm](z_CLI/spells/alarm-xphb.md)  
- [Alter Self](z_CLI/spells/alter-self-xphb.md)  
- [Animal Friendship](z_CLI/spells/animal-friendship-xphb.md)  
- [Animal Messenger](z_CLI/spells/animal-messenger-xphb.md)  
- [Animal Shapes](z_CLI/spells/animal-shapes-xphb.md)  
- [Animate Dead](z_CLI/spells/animate-dead-xphb.md)  
- [Animate Objects](z_CLI/spells/animate-objects-xphb.md)  
- [Antilife Shell](z_CLI/spells/antilife-shell-xphb.md)  
- [Antimagic Field](z_CLI/spells/antimagic-field-xphb.md)  
- [Antipathy/Sympathy](z_CLI/spells/antipathy-sympathy-xphb.md)  
- [Arcane Eye](z_CLI/spells/arcane-eye-xphb.md)  
- [Arcane Gate](z_CLI/spells/arcane-gate-xphb.md)  
- [Arcane Lock](z_CLI/spells/arcane-lock-xphb.md)  
- [Arcane Vigor](z_CLI/spells/arcane-vigor-xphb.md)  
- [Armor of Agathys](z_CLI/spells/armor-of-agathys-xphb.md)  
- [Arms of Hadar](z_CLI/spells/arms-of-hadar-xphb.md)  
- [Astral Projection](z_CLI/spells/astral-projection-xphb.md)  
- [Augury](z_CLI/spells/augury-xphb.md)  
- [Aura of Life](z_CLI/spells/aura-of-life-xphb.md)  
- [Aura of Purity](z_CLI/spells/aura-of-purity-xphb.md)  
- [Aura of Vitality](z_CLI/spells/aura-of-vitality-xphb.md)  
- [Awaken](z_CLI/spells/awaken-xphb.md)  

- [Bane](z_CLI/spells/bane-xphb.md)  
- [Banishing Smite](z_CLI/spells/banishing-smite-xphb.md)  
- [Banishment](z_CLI/spells/banishment-xphb.md)  
- [Barkskin](z_CLI/spells/barkskin-xphb.md)  
- [Beacon of Hope](z_CLI/spells/beacon-of-hope-xphb.md)  
- [Beast Sense](z_CLI/spells/beast-sense-xphb.md)  
- [Befuddlement](z_CLI/spells/befuddlement-xphb.md)  
- [Bestow Curse](z_CLI/spells/bestow-curse-xphb.md)  
- [Bigby's Hand](z_CLI/spells/bigbys-hand-xphb.md)  
- [Blade Barrier](z_CLI/spells/blade-barrier-xphb.md)  
- [Blade Ward](z_CLI/spells/blade-ward-xphb.md)  
- [Bless](z_CLI/spells/bless-xphb.md)  
- [Blight](z_CLI/spells/blight-xphb.md)  
- [Blinding Smite](z_CLI/spells/blinding-smite-xphb.md)  
- [Blindness/Deafness](z_CLI/spells/blindness-deafness-xphb.md)  
- [Blink](z_CLI/spells/blink-xphb.md)  
- [Blur](z_CLI/spells/blur-xphb.md)  
- [Burning Hands](z_CLI/spells/burning-hands-xphb.md)  

- [Call Lightning](z_CLI/spells/call-lightning-xphb.md)  
- [Calm Emotions](z_CLI/spells/calm-emotions-xphb.md)  
- [Chain Lightning](z_CLI/spells/chain-lightning-xphb.md)  
- [Charm Monster](z_CLI/spells/charm-monster-xphb.md)  
- [Charm Person](z_CLI/spells/charm-person-xphb.md)  
- [Chill Touch](z_CLI/spells/chill-touch-xphb.md)  
- [Chromatic Orb](z_CLI/spells/chromatic-orb-xphb.md)  
- [Circle of Death](z_CLI/spells/circle-of-death-xphb.md)  
- [Circle of Power](z_CLI/spells/circle-of-power-xphb.md)  
- [Clairvoyance](z_CLI/spells/clairvoyance-xphb.md)  
- [Clone](z_CLI/spells/clone-xphb.md)  
- [Cloud of Daggers](z_CLI/spells/cloud-of-daggers-xphb.md)  
- [Cloudkill](z_CLI/spells/cloudkill-xphb.md)  
- [Color Spray](z_CLI/spells/color-spray-xphb.md)  
- [Command](z_CLI/spells/command-xphb.md)  
- [Commune](z_CLI/spells/commune-xphb.md)  
- [Commune with Nature](z_CLI/spells/commune-with-nature-xphb.md)  
- [Compelled Duel](z_CLI/spells/compelled-duel-xphb.md)  
- [Comprehend Languages](z_CLI/spells/comprehend-languages-xphb.md)  
- [Compulsion](z_CLI/spells/compulsion-xphb.md)  
- [Cone of Cold](z_CLI/spells/cone-of-cold-xphb.md)  
- [Confusion](z_CLI/spells/confusion-xphb.md)  
- [Conjure Animals](z_CLI/spells/conjure-animals-xphb.md)  
- [Conjure Barrage](z_CLI/spells/conjure-barrage-xphb.md)  
- [Conjure Celestial](z_CLI/spells/conjure-celestial-xphb.md)  
- [Conjure Elemental](z_CLI/spells/conjure-elemental-xphb.md)  
- [Conjure Fey](z_CLI/spells/conjure-fey-xphb.md)  
- [Conjure Minor Elementals](z_CLI/spells/conjure-minor-elementals-xphb.md)  
- [Conjure Volley](z_CLI/spells/conjure-volley-xphb.md)  
- [Conjure Woodland Beings](z_CLI/spells/conjure-woodland-beings-xphb.md)  
- [Contact Other Plane](z_CLI/spells/contact-other-plane-xphb.md)  
- [Contagion](z_CLI/spells/contagion-xphb.md)  
- [Contingency](z_CLI/spells/contingency-xphb.md)  
- [Continual Flame](z_CLI/spells/continual-flame-xphb.md)  
- [Control Water](z_CLI/spells/control-water-xphb.md)  
- [Control Weather](z_CLI/spells/control-weather-xphb.md)  
- [Cordon of Arrows](z_CLI/spells/cordon-of-arrows-xphb.md)  
- [Counterspell](z_CLI/spells/counterspell-xphb.md)  
- [Create Food and Water](z_CLI/spells/create-food-and-water-xphb.md)  
- [Create or Destroy Water](z_CLI/spells/create-or-destroy-water-xphb.md)  
- [Create Undead](z_CLI/spells/create-undead-xphb.md)  
- [Creation](z_CLI/spells/creation-xphb.md)  
- [Crown of Madness](z_CLI/spells/crown-of-madness-xphb.md)  
- [Crusader's Mantle](z_CLI/spells/crusaders-mantle-xphb.md)  
- [Cure Wounds](z_CLI/spells/cure-wounds-xphb.md)  

- [Dancing Lights](z_CLI/spells/dancing-lights-xphb.md)  
- [Darkness](z_CLI/spells/darkness-xphb.md)  
- [Darkvision](z_CLI/spells/darkvision-xphb.md)  
- [Daylight](z_CLI/spells/daylight-xphb.md)  
- [Death Ward](z_CLI/spells/death-ward-xphb.md)  
- [Delayed Blast Fireball](z_CLI/spells/delayed-blast-fireball-xphb.md)  
- [Demiplane](z_CLI/spells/demiplane-xphb.md)  
- [Destructive Wave](z_CLI/spells/destructive-wave-xphb.md)  
- [Detect Evil and Good](z_CLI/spells/detect-evil-and-good-xphb.md)  
- [Detect Magic](z_CLI/spells/detect-magic-xphb.md)  
- [Detect Poison and Disease](z_CLI/spells/detect-poison-and-disease-xphb.md)  
- [Detect Thoughts](z_CLI/spells/detect-thoughts-xphb.md)  
- [Dimension Door](z_CLI/spells/dimension-door-xphb.md)  
- [Disguise Self](z_CLI/spells/disguise-self-xphb.md)  
- [Disintegrate](z_CLI/spells/disintegrate-xphb.md)  
- [Dispel Evil and Good](z_CLI/spells/dispel-evil-and-good-xphb.md)  
- [Dispel Magic](z_CLI/spells/dispel-magic-xphb.md)  
- [Dissonant Whispers](z_CLI/spells/dissonant-whispers-xphb.md)  
- [Divination](z_CLI/spells/divination-xphb.md)  
- [Divine Favor](z_CLI/spells/divine-favor-xphb.md)  
- [Divine Smite](z_CLI/spells/divine-smite-xphb.md)  
- [Divine Word](z_CLI/spells/divine-word-xphb.md)  
- [Dominate Beast](z_CLI/spells/dominate-beast-xphb.md)  
- [Dominate Monster](z_CLI/spells/dominate-monster-xphb.md)  
- [Dominate Person](z_CLI/spells/dominate-person-xphb.md)  
- [Dragon's Breath](z_CLI/spells/dragons-breath-xphb.md)  
- [Drawmij's Instant Summons](z_CLI/spells/drawmijs-instant-summons-xphb.md)  
- [Dream](z_CLI/spells/dream-xphb.md)  
- [Druidcraft](z_CLI/spells/druidcraft-xphb.md)  

- [Earthquake](z_CLI/spells/earthquake-xphb.md)  
- [Eldritch Blast](z_CLI/spells/eldritch-blast-xphb.md)  
- [Elemental Weapon](z_CLI/spells/elemental-weapon-xphb.md)  
- [Elementalism](z_CLI/spells/elementalism-xphb.md)  
- [Enhance Ability](z_CLI/spells/enhance-ability-xphb.md)  
- [Enlarge/Reduce](z_CLI/spells/enlarge-reduce-xphb.md)  
- [Ensnaring Strike](z_CLI/spells/ensnaring-strike-xphb.md)  
- [Entangle](z_CLI/spells/entangle-xphb.md)  
- [Enthrall](z_CLI/spells/enthrall-xphb.md)  
- [Etherealness](z_CLI/spells/etherealness-xphb.md)  
- [Evard's Black Tentacles](z_CLI/spells/evards-black-tentacles-xphb.md)  
- [Expeditious Retreat](z_CLI/spells/expeditious-retreat-xphb.md)  
- [Eyebite](z_CLI/spells/eyebite-xphb.md)  

- [Fabricate](z_CLI/spells/fabricate-xphb.md)  
- [Faerie Fire](z_CLI/spells/faerie-fire-xphb.md)  
- [False Life](z_CLI/spells/false-life-xphb.md)  
- [Fear](z_CLI/spells/fear-xphb.md)  
- [Feather Fall](z_CLI/spells/feather-fall-xphb.md)  
- [Feign Death](z_CLI/spells/feign-death-xphb.md)  
- [Find Familiar](z_CLI/spells/find-familiar-xphb.md)  
- [Find Steed](z_CLI/spells/find-steed-xphb.md)  
- [Find the Path](z_CLI/spells/find-the-path-xphb.md)  
- [Find Traps](z_CLI/spells/find-traps-xphb.md)  
- [Finger of Death](z_CLI/spells/finger-of-death-xphb.md)  
- [Fire Bolt](z_CLI/spells/fire-bolt-xphb.md)  
- [Fire Shield](z_CLI/spells/fire-shield-xphb.md)  
- [Fire Storm](z_CLI/spells/fire-storm-xphb.md)  
- [Fireball](z_CLI/spells/fireball-xphb.md)  
- [Flame Blade](z_CLI/spells/flame-blade-xphb.md)  
- [Flame Strike](z_CLI/spells/flame-strike-xphb.md)  
- [Flaming Sphere](z_CLI/spells/flaming-sphere-xphb.md)  
- [Flesh to Stone](z_CLI/spells/flesh-to-stone-xphb.md)  
- [Fly](z_CLI/spells/fly-xphb.md)  
- [Fog Cloud](z_CLI/spells/fog-cloud-xphb.md)  
- [Forbiddance](z_CLI/spells/forbiddance-xphb.md)  
- [Forcecage](z_CLI/spells/forcecage-xphb.md)  
- [Foresight](z_CLI/spells/foresight-xphb.md)  
- [Fount of Moonlight](z_CLI/spells/fount-of-moonlight-xphb.md)  
- [Freedom of Movement](z_CLI/spells/freedom-of-movement-xphb.md)  
- [Friends](z_CLI/spells/friends-xphb.md)  

- [Gaseous Form](z_CLI/spells/gaseous-form-xphb.md)  
- [Gate](z_CLI/spells/gate-xphb.md)  
- [Geas](z_CLI/spells/geas-xphb.md)  
- [Gentle Repose](z_CLI/spells/gentle-repose-xphb.md)  
- [Giant Insect](z_CLI/spells/giant-insect-xphb.md)  
- [Glibness](z_CLI/spells/glibness-xphb.md)  
- [Globe of Invulnerability](z_CLI/spells/globe-of-invulnerability-xphb.md)  
- [Glyph of Warding](z_CLI/spells/glyph-of-warding-xphb.md)  
- [Goodberry](z_CLI/spells/goodberry-xphb.md)  
- [Grasping Vine](z_CLI/spells/grasping-vine-xphb.md)  
- [Grease](z_CLI/spells/grease-xphb.md)  
- [Greater Invisibility](z_CLI/spells/greater-invisibility-xphb.md)  
- [Greater Restoration](z_CLI/spells/greater-restoration-xphb.md)  
- [Guardian of Faith](z_CLI/spells/guardian-of-faith-xphb.md)  
- [Guards and Wards](z_CLI/spells/guards-and-wards-xphb.md)  
- [Guidance](z_CLI/spells/guidance-xphb.md)  
- [Guiding Bolt](z_CLI/spells/guiding-bolt-xphb.md)  
- [Gust of Wind](z_CLI/spells/gust-of-wind-xphb.md)  

- [Hail of Thorns](z_CLI/spells/hail-of-thorns-xphb.md)  
- [Hallow](z_CLI/spells/hallow-xphb.md)  
- [Hallucinatory Terrain](z_CLI/spells/hallucinatory-terrain-xphb.md)  
- [Harm](z_CLI/spells/harm-xphb.md)  
- [Haste](z_CLI/spells/haste-xphb.md)  
- [Heal](z_CLI/spells/heal-xphb.md)  
- [Healing Word](z_CLI/spells/healing-word-xphb.md)  
- [Heat Metal](z_CLI/spells/heat-metal-xphb.md)  
- [Hellish Rebuke](z_CLI/spells/hellish-rebuke-xphb.md)  
- [Heroes' Feast](z_CLI/spells/heroes-feast-xphb.md)  
- [Heroism](z_CLI/spells/heroism-xphb.md)  
- [Hex](z_CLI/spells/hex-xphb.md)  
- [Hold Monster](z_CLI/spells/hold-monster-xphb.md)  
- [Hold Person](z_CLI/spells/hold-person-xphb.md)  
- [Holy Aura](z_CLI/spells/holy-aura-xphb.md)  
- [Hunger of Hadar](z_CLI/spells/hunger-of-hadar-xphb.md)  
- [Hunter's Mark](z_CLI/spells/hunters-mark-xphb.md)  
- [Hypnotic Pattern](z_CLI/spells/hypnotic-pattern-xphb.md)  

- [Ice Knife](z_CLI/spells/ice-knife-xphb.md)  
- [Ice Storm](z_CLI/spells/ice-storm-xphb.md)  
- [Identify](z_CLI/spells/identify-xphb.md)  
- [Illusory Script](z_CLI/spells/illusory-script-xphb.md)  
- [Imprisonment](z_CLI/spells/imprisonment-xphb.md)  
- [Incendiary Cloud](z_CLI/spells/incendiary-cloud-xphb.md)  
- [Inflict Wounds](z_CLI/spells/inflict-wounds-xphb.md)  
- [Insect Plague](z_CLI/spells/insect-plague-xphb.md)  
- [Invisibility](z_CLI/spells/invisibility-xphb.md)  

- [Jallarzi's Storm of Radiance](z_CLI/spells/jallarzis-storm-of-radiance-xphb.md)  
- [Jump](z_CLI/spells/jump-xphb.md)  

- [Knock](z_CLI/spells/knock-xphb.md)  

- [Legend Lore](z_CLI/spells/legend-lore-xphb.md)  
- [Leomund's Secret Chest](z_CLI/spells/leomunds-secret-chest-xphb.md)  
- [Leomund's Tiny Hut](z_CLI/spells/leomunds-tiny-hut-xphb.md)  
- [Lesser Restoration](z_CLI/spells/lesser-restoration-xphb.md)  
- [Levitate](z_CLI/spells/levitate-xphb.md)  
- [Light](z_CLI/spells/light-xphb.md)  
- [Lightning Arrow](z_CLI/spells/lightning-arrow-xphb.md)  
- [Lightning Bolt](z_CLI/spells/lightning-bolt-xphb.md)  
- [Locate Animals or Plants](z_CLI/spells/locate-animals-or-plants-xphb.md)  
- [Locate Creature](z_CLI/spells/locate-creature-xphb.md)  
- [Locate Object](z_CLI/spells/locate-object-xphb.md)  
- [Longstrider](z_CLI/spells/longstrider-xphb.md)  

- [Mage Armor](z_CLI/spells/mage-armor-xphb.md)  
- [Mage Hand](z_CLI/spells/mage-hand-xphb.md)  
- [Magic Circle](z_CLI/spells/magic-circle-xphb.md)  
- [Magic Jar](z_CLI/spells/magic-jar-xphb.md)  
- [Magic Missile](z_CLI/spells/magic-missile-xphb.md)  
- [Magic Mouth](z_CLI/spells/magic-mouth-xphb.md)  
- [Magic Weapon](z_CLI/spells/magic-weapon-xphb.md)  
- [Major Image](z_CLI/spells/major-image-xphb.md)  
- [Mass Cure Wounds](z_CLI/spells/mass-cure-wounds-xphb.md)  
- [Mass Heal](z_CLI/spells/mass-heal-xphb.md)  
- [Mass Healing Word](z_CLI/spells/mass-healing-word-xphb.md)  
- [Mass Suggestion](z_CLI/spells/mass-suggestion-xphb.md)  
- [Maze](z_CLI/spells/maze-xphb.md)  
- [Meld into Stone](z_CLI/spells/meld-into-stone-xphb.md)  
- [Melf's Acid Arrow](z_CLI/spells/melfs-acid-arrow-xphb.md)  
- [Mending](z_CLI/spells/mending-xphb.md)  
- [Message](z_CLI/spells/message-xphb.md)  
- [Meteor Swarm](z_CLI/spells/meteor-swarm-xphb.md)  
- [Mind Blank](z_CLI/spells/mind-blank-xphb.md)  
- [Mind Sliver](z_CLI/spells/mind-sliver-xphb.md)  
- [Mind Spike](z_CLI/spells/mind-spike-xphb.md)  
- [Minor Illusion](z_CLI/spells/minor-illusion-xphb.md)  
- [Mirage Arcane](z_CLI/spells/mirage-arcane-xphb.md)  
- [Mirror Image](z_CLI/spells/mirror-image-xphb.md)  
- [Mislead](z_CLI/spells/mislead-xphb.md)  
- [Misty Step](z_CLI/spells/misty-step-xphb.md)  
- [Modify Memory](z_CLI/spells/modify-memory-xphb.md)  
- [Moonbeam](z_CLI/spells/moonbeam-xphb.md)  
- [Mordenkainen's Faithful Hound](z_CLI/spells/mordenkainens-faithful-hound-xphb.md)  
- [Mordenkainen's Magnificent Mansion](z_CLI/spells/mordenkainens-magnificent-mansion-xphb.md)  
- [Mordenkainen's Private Sanctum](z_CLI/spells/mordenkainens-private-sanctum-xphb.md)  
- [Mordenkainen's Sword](z_CLI/spells/mordenkainens-sword-xphb.md)  
- [Move Earth](z_CLI/spells/move-earth-xphb.md)  

- [Nondetection](z_CLI/spells/nondetection-xphb.md)  
- [Nystul's Magic Aura](z_CLI/spells/nystuls-magic-aura-xphb.md)  

- [Otiluke's Freezing Sphere](z_CLI/spells/otilukes-freezing-sphere-xphb.md)  
- [Otiluke's Resilient Sphere](z_CLI/spells/otilukes-resilient-sphere-xphb.md)  
- [Otto's Irresistible Dance](z_CLI/spells/ottos-irresistible-dance-xphb.md)  

- [Pass without Trace](z_CLI/spells/pass-without-trace-xphb.md)  
- [Passwall](z_CLI/spells/passwall-xphb.md)  
- [Phantasmal Force](z_CLI/spells/phantasmal-force-xphb.md)  
- [Phantasmal Killer](z_CLI/spells/phantasmal-killer-xphb.md)  
- [Phantom Steed](z_CLI/spells/phantom-steed-xphb.md)  
- [Planar Ally](z_CLI/spells/planar-ally-xphb.md)  
- [Planar Binding](z_CLI/spells/planar-binding-xphb.md)  
- [Plane Shift](z_CLI/spells/plane-shift-xphb.md)  
- [Plant Growth](z_CLI/spells/plant-growth-xphb.md)  
- [Poison Spray](z_CLI/spells/poison-spray-xphb.md)  
- [Polymorph](z_CLI/spells/polymorph-xphb.md)  
- [Power Word Fortify](z_CLI/spells/power-word-fortify-xphb.md)  
- [Power Word Heal](z_CLI/spells/power-word-heal-xphb.md)  
- [Power Word Kill](z_CLI/spells/power-word-kill-xphb.md)  
- [Power Word Stun](z_CLI/spells/power-word-stun-xphb.md)  
- [Prayer of Healing](z_CLI/spells/prayer-of-healing-xphb.md)  
- [Prestidigitation](z_CLI/spells/prestidigitation-xphb.md)  
- [Prismatic Spray](z_CLI/spells/prismatic-spray-xphb.md)  
- [Prismatic Wall](z_CLI/spells/prismatic-wall-xphb.md)  
- [Produce Flame](z_CLI/spells/produce-flame-xphb.md)  
- [Programmed Illusion](z_CLI/spells/programmed-illusion-xphb.md)  
- [Project Image](z_CLI/spells/project-image-xphb.md)  
- [Protection from Energy](z_CLI/spells/protection-from-energy-xphb.md)  
- [Protection from Evil and Good](z_CLI/spells/protection-from-evil-and-good-xphb.md)  
- [Protection from Poison](z_CLI/spells/protection-from-poison-xphb.md)  
- [Purify Food and Drink](z_CLI/spells/purify-food-and-drink-xphb.md)  

- [Raise Dead](z_CLI/spells/raise-dead-xphb.md)  
- [Rary's Telepathic Bond](z_CLI/spells/rarys-telepathic-bond-xphb.md)  
- [Ray of Enfeeblement](z_CLI/spells/ray-of-enfeeblement-xphb.md)  
- [Ray of Frost](z_CLI/spells/ray-of-frost-xphb.md)  
- [Ray of Sickness](z_CLI/spells/ray-of-sickness-xphb.md)  
- [Regenerate](z_CLI/spells/regenerate-xphb.md)  
- [Reincarnate](z_CLI/spells/reincarnate-xphb.md)  
- [Remove Curse](z_CLI/spells/remove-curse-xphb.md)  
- [Resistance](z_CLI/spells/resistance-xphb.md)  
- [Resurrection](z_CLI/spells/resurrection-xphb.md)  
- [Reverse Gravity](z_CLI/spells/reverse-gravity-xphb.md)  
- [Revivify](z_CLI/spells/revivify-xphb.md)  
- [Rope Trick](z_CLI/spells/rope-trick-xphb.md)  

- [Sacred Flame](z_CLI/spells/sacred-flame-xphb.md)  
- [Sanctuary](z_CLI/spells/sanctuary-xphb.md)  
- [Scorching Ray](z_CLI/spells/scorching-ray-xphb.md)  
- [Scrying](z_CLI/spells/scrying-xphb.md)  
- [Searing Smite](z_CLI/spells/searing-smite-xphb.md)  
- [See Invisibility](z_CLI/spells/see-invisibility-xphb.md)  
- [Seeming](z_CLI/spells/seeming-xphb.md)  
- [Sending](z_CLI/spells/sending-xphb.md)  
- [Sequester](z_CLI/spells/sequester-xphb.md)  
- [Shapechange](z_CLI/spells/shapechange-xphb.md)  
- [Shatter](z_CLI/spells/shatter-xphb.md)  
- [Shield](z_CLI/spells/shield-xphb.md)  
- [Shield of Faith](z_CLI/spells/shield-of-faith-xphb.md)  
- [Shillelagh](z_CLI/spells/shillelagh-xphb.md)  
- [Shining Smite](z_CLI/spells/shining-smite-xphb.md)  
- [Shocking Grasp](z_CLI/spells/shocking-grasp-xphb.md)  
- [Silence](z_CLI/spells/silence-xphb.md)  
- [Silent Image](z_CLI/spells/silent-image-xphb.md)  
- [Simulacrum](z_CLI/spells/simulacrum-xphb.md)  
- [Sleep](z_CLI/spells/sleep-xphb.md)  
- [Sleet Storm](z_CLI/spells/sleet-storm-xphb.md)  
- [Slow](z_CLI/spells/slow-xphb.md)  
- [Sorcerous Burst](z_CLI/spells/sorcerous-burst-xphb.md)  
- [Spare the Dying](z_CLI/spells/spare-the-dying-xphb.md)  
- [Speak with Animals](z_CLI/spells/speak-with-animals-xphb.md)  
- [Speak with Dead](z_CLI/spells/speak-with-dead-xphb.md)  
- [Speak with Plants](z_CLI/spells/speak-with-plants-xphb.md)  
- [Spider Climb](z_CLI/spells/spider-climb-xphb.md)  
- [Spike Growth](z_CLI/spells/spike-growth-xphb.md)  
- [Spirit Guardians](z_CLI/spells/spirit-guardians-xphb.md)  
- [Spiritual Weapon](z_CLI/spells/spiritual-weapon-xphb.md)  
- [Staggering Smite](z_CLI/spells/staggering-smite-xphb.md)  
- [Starry Wisp](z_CLI/spells/starry-wisp-xphb.md)  
- [Steel Wind Strike](z_CLI/spells/steel-wind-strike-xphb.md)  
- [Stinking Cloud](z_CLI/spells/stinking-cloud-xphb.md)  
- [Stone Shape](z_CLI/spells/stone-shape-xphb.md)  
- [Stoneskin](z_CLI/spells/stoneskin-xphb.md)  
- [Storm of Vengeance](z_CLI/spells/storm-of-vengeance-xphb.md)  
- [Suggestion](z_CLI/spells/suggestion-xphb.md)  
- [Summon Aberration](z_CLI/spells/summon-aberration-xphb.md)  
- [Summon Beast](z_CLI/spells/summon-beast-xphb.md)  
- [Summon Celestial](z_CLI/spells/summon-celestial-xphb.md)  
- [Summon Construct](z_CLI/spells/summon-construct-xphb.md)  
- [Summon Dragon](z_CLI/spells/summon-dragon-xphb.md)  
- [Summon Elemental](z_CLI/spells/summon-elemental-xphb.md)  
- [Summon Fey](z_CLI/spells/summon-fey-xphb.md)  
- [Summon Fiend](z_CLI/spells/summon-fiend-xphb.md)  
- [Summon Undead](z_CLI/spells/summon-undead-xphb.md)  
- [Sunbeam](z_CLI/spells/sunbeam-xphb.md)  
- [Sunburst](z_CLI/spells/sunburst-xphb.md)  
- [Swift Quiver](z_CLI/spells/swift-quiver-xphb.md)  
- [Symbol](z_CLI/spells/symbol-xphb.md)  
- [Synaptic Static](z_CLI/spells/synaptic-static-xphb.md)  

- [Tasha's Bubbling Cauldron](z_CLI/spells/tashas-bubbling-cauldron-xphb.md)  
- [Tasha's Hideous Laughter](z_CLI/spells/tashas-hideous-laughter-xphb.md)  
- [Telekinesis](z_CLI/spells/telekinesis-xphb.md)  
- [Telepathy](z_CLI/spells/telepathy-xphb.md)  
- [Teleport](z_CLI/spells/teleport-xphb.md)  
- [Teleportation Circle](z_CLI/spells/teleportation-circle-xphb.md)  
- [Tenser's Floating Disk](z_CLI/spells/tensers-floating-disk-xphb.md)  
- [Thaumaturgy](z_CLI/spells/thaumaturgy-xphb.md)  
- [Thorn Whip](z_CLI/spells/thorn-whip-xphb.md)  
- [Thunderclap](z_CLI/spells/thunderclap-xphb.md)  
- [Thunderous Smite](z_CLI/spells/thunderous-smite-xphb.md)  
- [Thunderwave](z_CLI/spells/thunderwave-xphb.md)  
- [Time Stop](z_CLI/spells/time-stop-xphb.md)  
- [Toll the Dead](z_CLI/spells/toll-the-dead-xphb.md)  
- [Tongues](z_CLI/spells/tongues-xphb.md)  
- [Transport via Plants](z_CLI/spells/transport-via-plants-xphb.md)  
- [Tree Stride](z_CLI/spells/tree-stride-xphb.md)  
- [True Polymorph](z_CLI/spells/true-polymorph-xphb.md)  
- [True Resurrection](z_CLI/spells/true-resurrection-xphb.md)  
- [True Seeing](z_CLI/spells/true-seeing-xphb.md)  
- [True Strike](z_CLI/spells/true-strike-xphb.md)  
- [Tsunami](z_CLI/spells/tsunami-xphb.md)  

- [Unseen Servant](z_CLI/spells/unseen-servant-xphb.md)  

- [Vampiric Touch](z_CLI/spells/vampiric-touch-xphb.md)  
- [Vicious Mockery](z_CLI/spells/vicious-mockery-xphb.md)  
- [Vitriolic Sphere](z_CLI/spells/vitriolic-sphere-xphb.md)  

- [Wall of Fire](z_CLI/spells/wall-of-fire-xphb.md)  
- [Wall of Force](z_CLI/spells/wall-of-force-xphb.md)  
- [Wall of Ice](z_CLI/spells/wall-of-ice-xphb.md)  
- [Wall of Stone](z_CLI/spells/wall-of-stone-xphb.md)  
- [Wall of Thorns](z_CLI/spells/wall-of-thorns-xphb.md)  
- [Warding Bond](z_CLI/spells/warding-bond-xphb.md)  
- [Water Breathing](z_CLI/spells/water-breathing-xphb.md)  
- [Water Walk](z_CLI/spells/water-walk-xphb.md)  
- [Web](z_CLI/spells/web-xphb.md)  
- [Weird](z_CLI/spells/weird-xphb.md)  
- [Wind Walk](z_CLI/spells/wind-walk-xphb.md)  
- [Wind Wall](z_CLI/spells/wind-wall-xphb.md)  
- [Wish](z_CLI/spells/wish-xphb.md)  
- [Witch Bolt](z_CLI/spells/witch-bolt-xphb.md)  
- [Word of Radiance](z_CLI/spells/word-of-radiance-xphb.md)  
- [Word of Recall](z_CLI/spells/word-of-recall-xphb.md)  
- [Wrathful Smite](z_CLI/spells/wrathful-smite-xphb.md)  

- [Yolande's Regal Presence](z_CLI/spells/yolandes-regal-presence-xphb.md)  

- [Zone of Truth](z_CLI/spells/zone-of-truth-xphb.md)