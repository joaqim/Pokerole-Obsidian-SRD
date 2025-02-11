---
Ability1: Magnet Pull
Ability2: Sturdy
BookSprite: SRD-magneton-BookSprite.png
BoxSprite: SRD-magneton-BoxSprite.png
DexCategory: Magnet Pokemon
DexDescription: Sometimes three Magnemites fuse into this Pokemon; other times a single
  one sprouts two others. This species is greatly affected by magnetic fields. Magnetons
  are eager to please their trainers.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Magnemite]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Magnezone]]'
  Speed: Slow
GenderType: N
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Analytic
HomeSprite: SRD-magneton-HomeSprite.png
Image: magneton.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Supersonic|Supersonic]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tri Attack|Tri Attack]]'
- - Beginner
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Beginner
  - '[[SRD-Sonic Boom|Sonic Boom]]'
- - Beginner
  - '[[SRD-Electric Terrain|Electric Terrain]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Amateur
  - '[[SRD-Magnet Bomb|Magnet Bomb]]'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Mirror Shot|Mirror Shot]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Electro Ball|Electro Ball]]'
- - Amateur
  - '[[SRD-Flash Cannon|Flash Cannon]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Amateur
  - '[[SRD-Lock-On|Lock-On]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - Ace
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Gravity|Gravity]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Signal Beam|Signal Beam]]'
Number: 82
ShuffleToken: SRD-magneton-ShuffleToken.png
Type1: Electric
Type2: Steel
Weight:
  Kilograms: 60.0
  Pounds: 132.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-magneton-BookSprite.png|wsmall]]
> ![[SRD-magneton-HomeSprite.png]]
> ![[SRD-magneton-BoxSprite.png|htiny]]
> ![[SRD-magneton-ShuffleToken.png|wsmall]]


*Magnet Pokemon*
*Sometimes three Magnemites fuse into this Pokemon; other times a single one sprouts two others. This species is greatly affected by magnetic fields. Magnetons are eager to please their trainers.*

**DexID**:: 0082
**Name**:: Magneton
**Type**:: Electric / Steel
**Abilities**:: [[SRD-Magnet Pull|Magnet Pull]] / [[SRD-Sturdy|Sturdy]] ([[SRD-Analytic|Analytic]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::6)     |

**Height**: 3'3" / 1.0m
**Weight**: 132.3lbs / 60.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Magnemite]] | Level  | Medium  |
| To        | [[SRD-Magnezone]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Magneton.md"
flatten moves as T
where file.path = this.file.path
```
