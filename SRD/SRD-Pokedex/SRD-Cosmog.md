---
Ability1: Unaware
Ability2: ''
BookSprite: SRD-cosmog-BookSprite.png
BoxSprite: SRD-cosmog-BoxSprite.png
DexCategory: No Data
DexDescription: A creature like this was observed on a telescope. It is rumored to
  be a Pokemon from another world, but no specific details are known.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Cosmoem]]'
  Speed: Unknown
GenderType: N
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: ''
HomeSprite: SRD-cosmog-HomeSprite.png
Image: cosmog.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Splash|Splash]]'
- - Starter
  - '[[SRD-Teleport|Teleport]]'
Number: 789
ShuffleToken: SRD-cosmog-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 0.1
  Pounds: 0.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cosmog-BookSprite.png|wsmall]]
> ![[SRD-cosmog-HomeSprite.png]]
> ![[SRD-cosmog-BoxSprite.png|htiny]]
> ![[SRD-cosmog-ShuffleToken.png|wsmall]]


*No Data*
*A creature like this was observed on a telescope. It is rumored to be a Pokemon from another world, but no specific details are known.*

**DexID**:: 0789
**Name**:: Cosmog
**Type**:: Psychic
**Abilities**:: [[SRD-Unaware|Unaware]]
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 0'7" / 0.2m
**Weight**: 0.2lbs / 0.1kg
**Good Starter**:: No
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Cosmoem]] | Level  | Unknown |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Cosmog.md"
flatten moves as T
where file.path = this.file.path
```
