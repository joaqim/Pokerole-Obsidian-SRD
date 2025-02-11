---
Ability1: Swift Swim
Ability2: Rain Dish
BookSprite: SRD-lotad-BookSprite.png
BoxSprite: SRD-lotad-BoxSprite.png
DexCategory: Water Weed Pokemon
DexDescription: They live in ponds and lakes, floating atop the water. The big leaf
  on their head is known to act as a ferry for smaller Pokemon. The leaf is delicate
  and needs constant watering or else Lotad will grow sick.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Lombre]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Own Tempo
HomeSprite: SRD-lotad-HomeSprite.png
Image: lotad.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - Beginner
  - '[[SRD-Nature Power|Nature Power]]'
- - Beginner
  - '[[SRD-Bubble|Bubble]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Mist|Mist]]'
- - Amateur
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Ace
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Ace
  - '[[SRD-Leech Seed|Leech Seed]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Energy Ball|Energy Ball]]'
- - Pro
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Pro
  - '[[SRD-Flail|Flail]]'
Number: 270
ShuffleToken: SRD-lotad-ShuffleToken.png
Type1: Water
Type2: Grass
Weight:
  Kilograms: 2.6
  Pounds: 5.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-lotad-BookSprite.png|wsmall]]
> ![[SRD-lotad-HomeSprite.png]]
> ![[SRD-lotad-BoxSprite.png|htiny]]
> ![[SRD-lotad-ShuffleToken.png|wsmall]]


*Water Weed Pokemon*
*They live in ponds and lakes, floating atop the water. The big leaf on their head is known to act as a ferry for smaller Pokemon. The leaf is delicate and needs constant watering or else Lotad will grow sick.*

**DexID**:: 0270
**Name**:: Lotad
**Type**:: Water / Grass
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] / [[SRD-Rain Dish|Rain Dish]] ([[SRD-Own Tempo|Own Tempo]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 5.7lbs / 2.6kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| To        | [[SRD-Lombre]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Lotad.md"
flatten moves as T
where file.path = this.file.path
```
