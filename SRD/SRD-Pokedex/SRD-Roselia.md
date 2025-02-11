---
Ability1: Natural Cure
Ability2: Poison Point
BookSprite: SRD-roselia-BookSprite.png
BoxSprite: SRD-roselia-BoxSprite.png
DexCategory: Thorn Pokemon
DexDescription: They live among rose bushes, shooting sharp poisonous thorns to anyone
  who tries to steal one of their flowers. Their aroma brings serenity. They need
  clean water to grow beautiful.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Stat
  Pokemon: '[[SRD-Budew]]'
  Stat: Happiness
  Value: 4
- Evolves: To
  Item: Shiny Stone
  Kind: Stone
  Pokemon: '[[SRD-Roserade]]'
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Leaf Guard
HomeSprite: SRD-roselia-HomeSprite.png
Image: roselia.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growth|Growth]]'
- - Beginner
  - '[[SRD-Poison Sting|Poison Sting]]'
- - Beginner
  - '[[SRD-Stun Spore|Stun Spore]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Amateur
  - '[[SRD-Grass Whistle|Grass Whistle]]'
- - Amateur
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Amateur
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[SRD-Ingrain|Ingrain]]'
- - Amateur
  - '[[SRD-Petal Dance|Petal Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Toxic|Toxic]]'
- - Ace
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Ace
  - '[[SRD-Synthesis|Synthesis]]'
- - Ace
  - '[[SRD-Petal Blizzard|Petal Blizzard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Worry Seed|Worry Seed]]'
- - Pro
  - '[[SRD-Spikes|Spikes]]'
- - Pro
  - '[[SRD-Extrasensory|Extrasensory]]'
Number: 315
ShuffleToken: SRD-roselia-ShuffleToken.png
Type1: Grass
Type2: Poison
Weight:
  Kilograms: 2.0
  Pounds: 4.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-roselia-BookSprite.png|wsmall]]
> ![[SRD-roselia-HomeSprite.png]]
> ![[SRD-roselia-BoxSprite.png|htiny]]
> ![[SRD-roselia-ShuffleToken.png|wsmall]]


*Thorn Pokemon*
*They live among rose bushes, shooting sharp poisonous thorns to anyone who tries to steal one of their flowers. Their aroma brings serenity. They need clean water to grow beautiful.*

**DexID**:: 0315
**Name**:: Roselia
**Type**:: Grass / Poison
**Abilities**:: [[SRD-Natural Cure|Natural Cure]] / [[SRD-Poison Point|Poison Point]] ([[SRD-Leaf Guard|Leaf Guard]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 1'0" / 0.3m
**Weight**: 4.4lbs / 2.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Stat      | Value   | Item        |
|:----------|:-----------------|:-------|:----------|:--------|:------------|
| From      | [[SRD-Budew]]    | Stat   | Happiness | 4.0     |             |
| To        | [[SRD-Roserade]] | Stone  |           |         | Shiny Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Roselia.md"
flatten moves as T
where file.path = this.file.path
```
