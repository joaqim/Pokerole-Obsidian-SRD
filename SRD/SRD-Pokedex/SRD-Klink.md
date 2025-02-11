---
Ability1: Plus
Ability2: Minus
BookSprite: SRD-klink-BookSprite.png
BoxSprite: SRD-klink-BoxSprite.png
DexCategory: Gear Pokemon
DexDescription: This two strange Pokemon are merged into one. Interlocking their bodies
  and spinning around will generate the energy they need to live. Their only way to
  communicate is through their eyes.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Klang]]'
  Speed: Medium
GenderType: N
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Clear Body
HomeSprite: SRD-klink-HomeSprite.png
Image: klink.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Vice Grip|Vice Grip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Charge|Charge]]'
- - Beginner
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Gear Grind|Gear Grind]]'
- - Amateur
  - '[[SRD-Bind|Bind]]'
- - Amateur
  - '[[SRD-Charge Beam|Charge Beam]]'
- - Amateur
  - '[[SRD-Autotomize|Autotomize]]'
- - Amateur
  - '[[SRD-Mirror Shot|Mirror Shot]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Discharge|Discharge]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Shift Gear|Shift Gear]]'
- - Ace
  - '[[SRD-Lock-On|Lock-On]]'
- - Ace
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Pro
  - '[[SRD-Gravity|Gravity]]'
Number: 599
ShuffleToken: SRD-klink-ShuffleToken.png
Type1: Steel
Type2: ''
Weight:
  Kilograms: 21.0
  Pounds: 46.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-klink-BookSprite.png|wsmall]]
> ![[SRD-klink-HomeSprite.png]]
> ![[SRD-klink-BoxSprite.png|htiny]]
> ![[SRD-klink-ShuffleToken.png|wsmall]]


*Gear Pokemon*
*This two strange Pokemon are merged into one. Interlocking their bodies and spinning around will generate the energy they need to live. Their only way to communicate is through their eyes.*

**DexID**:: 0599
**Name**:: Klink
**Type**:: Steel
**Abilities**:: [[SRD-Plus|Plus]] / [[SRD-Minus|Minus]] ([[SRD-Clear Body|Clear Body]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'0" / 0.3m
**Weight**: 46.3lbs / 21.0kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon       | Kind   | Speed   |
|:----------|:--------------|:-------|:--------|
| To        | [[SRD-Klang]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Klink.md"
flatten moves as T
where file.path = this.file.path
```
