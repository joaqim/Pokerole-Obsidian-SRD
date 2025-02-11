---
Ability1: Weak Armor
Ability2: ''
BookSprite: SRD-cursola-BookSprite.png
BoxSprite: SRD-cursola-BoxSprite.png
DexCategory: Coral Pokemon
DexDescription: "The ectoplasm serves as protection for its soul, do not touch it\
  \ or you\u2019ll become stiff as stone. This Pokemon longs for the days where coral\
  \ reefs were full of life, it holds a grudge to those who destroyed them."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Corsola (Galarian Form)]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Perish Body
HomeSprite: SRD-cursola-HomeSprite.png
Image: cursola.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - Beginner
  - '[[SRD-Disable|Disable]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Spite|Spite]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Hex|Hex]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Strength Sap|Strength Sap]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Power Gem|Power Gem]]'
- - Ace
  - '[[SRD-Night Shade|Night Shade]]'
- - Ace
  - '[[SRD-Grudge|Grudge]]'
- - Ace
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - Ace
  - '[[SRD-Perish Song|Perish Song]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Liquidation|Liquidation]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Destiny Bond|Destiny Bond]]'
Number: 864
ShuffleToken: SRD-cursola-ShuffleToken.png
Type1: Ghost
Type2: ''
Weight:
  Kilograms: 0.4
  Pounds: 0.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cursola-BookSprite.png|wsmall]]
> ![[SRD-cursola-HomeSprite.png]]
> ![[SRD-cursola-BoxSprite.png|htiny]]
> ![[SRD-cursola-ShuffleToken.png|wsmall]]


*Coral Pokemon*
*The ectoplasm serves as protection for its soul, do not touch it or you’ll become stiff as stone. This Pokemon longs for the days where coral reefs were full of life, it holds a grudge to those who destroyed them.*

**DexID**:: 0864
**Name**:: Cursola
**Type**:: Ghost
**Abilities**:: [[SRD-Weak Armor|Weak Armor]] ([[SRD-Perish Body|Perish Body]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::4)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'3" / 1.0m
**Weight**: 0.9lbs / 0.4kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                         | Kind   | Speed   |
|:----------|:--------------------------------|:-------|:--------|
| From      | [[SRD-Corsola (Galarian Form)]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Cursola.md"
flatten moves as T
where file.path = this.file.path
```
