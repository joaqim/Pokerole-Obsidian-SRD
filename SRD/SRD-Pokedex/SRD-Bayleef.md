---
Ability1: Overgrow
Ability2: ''
BookSprite: SRD-bayleef-BookSprite.png
BoxSprite: SRD-bayleef-BoxSprite.png
DexCategory: Leaf Pokemon
DexDescription: A spicy fragrance emanates from around its neck that makes it feisty
  and impetuous. It sheds its leaves every couple of weeks after the aroma diminishes
  and its mood also becomes calmer.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Chikorita]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Meganium]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Leaf Guard
HomeSprite: SRD-bayleef-HomeSprite.png
Image: bayleef.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Beginner
  - '[[SRD-Poison Powder|Poison Powder]]'
- - Beginner
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Reflect|Reflect]]'
- - Amateur
  - '[[SRD-Synthesis|Synthesis]]'
- - Amateur
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Amateur
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Safeguard|Safeguard]]'
- - Ace
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Ace
  - '[[SRD-Solar Beam|Solar Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Pro
  - '[[SRD-Grass Pledge|Grass Pledge]]'
- - Pro
  - '[[SRD-Grassy Terrain|Grassy Terrain]]'
Number: 153
ShuffleToken: SRD-bayleef-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 15.8
  Pounds: 34.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-bayleef-BookSprite.png|wsmall]]
> ![[SRD-bayleef-HomeSprite.png]]
> ![[SRD-bayleef-BoxSprite.png|htiny]]
> ![[SRD-bayleef-ShuffleToken.png|wsmall]]


*Leaf Pokemon*
*A spicy fragrance emanates from around its neck that makes it feisty and impetuous. It sheds its leaves every couple of weeks after the aroma diminishes and its mood also becomes calmer.*

**DexID**:: 0153
**Name**:: Bayleef
**Type**:: Grass
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Leaf Guard|Leaf Guard]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 34.8lbs / 15.8kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Chikorita]] | Level  | Medium  |
| To        | [[SRD-Meganium]]  | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Bayleef.md"
flatten moves as T
where file.path = this.file.path
```
