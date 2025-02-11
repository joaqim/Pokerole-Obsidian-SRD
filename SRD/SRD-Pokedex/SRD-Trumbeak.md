---
Ability1: Keen Eye
Ability2: Skill Link
BookSprite: SRD-trumbeak-BookSprite.png
BoxSprite: SRD-trumbeak-BoxSprite.png
DexCategory: Bugle Beak Pokemon
DexDescription: This Pokemon bends its beak to produce a variety of sounds, much to
  the annoyance of the neighbors. It also shoots a burst of berry seeds to its foes,
  prey, or an unsuspecting passerby.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Pikipek]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Toucannon]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Pickup
HomeSprite: SRD-trumbeak-HomeSprite.png
Image: trumbeak.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Peck|Peck]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rock Smash|Rock Smash]]'
- - Beginner
  - '[[SRD-Echoed Voice|Echoed Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Amateur
  - '[[SRD-Supersonic|Supersonic]]'
- - Amateur
  - '[[SRD-Pluck|Pluck]]'
- - Amateur
  - '[[SRD-Roost|Roost]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Drill Peck|Drill Peck]]'
- - Ace
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - Ace
  - '[[SRD-Feather Dance|Feather Dance]]'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Uproar|Uproar]]'
- - Pro
  - '[[SRD-Tailwind|Tailwind]]'
- - Pro
  - '[[SRD-Mirror Move|Mirror Move]]'
Number: 732
ShuffleToken: SRD-trumbeak-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 14.8
  Pounds: 32.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-trumbeak-BookSprite.png|wsmall]]
> ![[SRD-trumbeak-HomeSprite.png]]
> ![[SRD-trumbeak-BoxSprite.png|htiny]]
> ![[SRD-trumbeak-ShuffleToken.png|wsmall]]


*Bugle Beak Pokemon*
*This Pokemon bends its beak to produce a variety of sounds, much to the annoyance of the neighbors. It also shoots a burst of berry seeds to its foes, prey, or an unsuspecting passerby.*

**DexID**:: 0732
**Name**:: Trumbeak
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Skill Link|Skill Link]] ([[SRD-Pickup|Pickup]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 32.6lbs / 14.8kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Pikipek]]   | Level  | Medium  |
| To        | [[SRD-Toucannon]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Trumbeak.md"
flatten moves as T
where file.path = this.file.path
```
