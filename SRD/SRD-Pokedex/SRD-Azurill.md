---
Ability1: Thick Fat
Ability2: Huge Power
BookSprite: SRD-azurill-BookSprite.png
BoxSprite: SRD-azurill-BoxSprite.png
DexCategory: Polka Dot Pokemon
DexDescription: They use their tail as a lasso. When they throw their ball, Azurills
  get dragged along with it. They are commonly seen bouncing and playing with other
  Pokemon in the beach. They love fruit paps.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Stat
  Pokemon: '[[SRD-Marill]]'
  Stat: Happiness
  Value: 4
GenderType: ''
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: Sap Sipper
HomeSprite: SRD-azurill-HomeSprite.png
Image: azurill.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Splash|Splash]]'
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Water Sport|Water Sport]]'
- - Beginner
  - '[[SRD-Bubble|Bubble]]'
- - Beginner
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bounce|Bounce]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Tickle|Tickle]]'
- - Pro
  - '[[SRD-Sing|Sing]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
Number: 298
ShuffleToken: SRD-azurill-ShuffleToken.png
Type1: Normal
Type2: Fairy
Weight:
  Kilograms: 2.0
  Pounds: 4.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-azurill-BookSprite.png|wsmall]]
> ![[SRD-azurill-HomeSprite.png]]
> ![[SRD-azurill-BoxSprite.png|htiny]]
> ![[SRD-azurill-ShuffleToken.png|wsmall]]


*Polka Dot Pokemon*
*They use their tail as a lasso. When they throw their ball, Azurills get dragged along with it. They are commonly seen bouncing and playing with other Pokemon in the beach. They love fruit paps.*

**DexID**:: 0298
**Name**:: Azurill
**Type**:: Normal / Fairy
**Abilities**:: [[SRD-Thick Fat|Thick Fat]] / [[SRD-Huge Power|Huge Power]] ([[SRD-Sap Sipper|Sap Sipper]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 0'7" / 0.2m
**Weight**: 4.4lbs / 2.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon        | Kind   | Stat      |   Value |
|:----------|:---------------|:-------|:----------|--------:|
| To        | [[SRD-Marill]] | Stat   | Happiness |       4 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Azurill.md"
flatten moves as T
where file.path = this.file.path
```
