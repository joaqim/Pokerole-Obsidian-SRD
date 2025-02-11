---
Ability1: Shed Skin
Ability2: ''
BookSprite: SRD-silcoon-BookSprite.png
BoxSprite: SRD-silcoon-BoxSprite.png
DexCategory: Cocoon Pokemon
DexDescription: They tether themselves to tree branches while they wait to evolve.
  Sometimes they peek from a small hole in the cocoon. Silcoons feed only on raindrops.
  If Wrumple lived among flowers, it evolves to Silcoon.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Wurmple]]'
  Speed: Fast
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Beautifly]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: ''
HomeSprite: SRD-silcoon-HomeSprite.png
Image: silcoon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Electroweb|Electroweb]]'
Number: 266
ShuffleToken: SRD-silcoon-ShuffleToken.png
Type1: Bug
Type2: ''
Weight:
  Kilograms: 10.0
  Pounds: 22.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-silcoon-BookSprite.png|wsmall]]
> ![[SRD-silcoon-HomeSprite.png]]
> ![[SRD-silcoon-BoxSprite.png|htiny]]
> ![[SRD-silcoon-ShuffleToken.png|wsmall]]


*Cocoon Pokemon*
*They tether themselves to tree branches while they wait to evolve. Sometimes they peek from a small hole in the cocoon. Silcoons feed only on raindrops. If Wrumple lived among flowers, it evolves to Silcoon.*

**DexID**:: 0266
**Name**:: Silcoon
**Type**:: Bug
**Abilities**:: [[SRD-Shed Skin|Shed Skin]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'0" / 0.6m
**Weight**: 22.0lbs / 10.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Wurmple]]   | Level  | Fast    |
| To        | [[SRD-Beautifly]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Silcoon.md"
flatten moves as T
where file.path = this.file.path
```
