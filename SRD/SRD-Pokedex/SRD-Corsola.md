---
Ability1: Hustle
Ability2: Natural Cure
BookSprite: SRD-corsola-BookSprite.png
BoxSprite: SRD-corsola-BoxSprite.png
DexCategory: Coral Pokemon
DexDescription: People and Pokemon build their communities on top of reefs of these
  creatures which shine with seven colors in sunlight. Their corals have healing qualities
  and their presence wards against disasters.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Regenerator
HomeSprite: SRD-corsola-HomeSprite.png
Image: corsola.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Harden|Harden]]'
- - Beginner
  - '[[SRD-Bubble|Bubble]]'
- - Beginner
  - '[[SRD-Recover|Recover]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Refresh|Refresh]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Amateur
  - '[[SRD-Spike Cannon|Spike Cannon]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Amateur
  - '[[SRD-Endure|Endure]]'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Ace
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - Ace
  - '[[SRD-Earth Power|Earth Power]]'
- - Ace
  - '[[SRD-Flail|Flail]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Head Smash|Head Smash]]'
- - Pro
  - '[[SRD-Screech|Screech]]'
- - Pro
  - '[[SRD-Whirlpool|Whirlpool]]'
Number: 222
ShuffleToken: SRD-corsola-ShuffleToken.png
Type1: Water
Type2: Rock
Weight:
  Kilograms: 5.0
  Pounds: 11.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-corsola-BookSprite.png|wsmall]]
> ![[SRD-corsola-HomeSprite.png]]
> ![[SRD-corsola-BoxSprite.png|htiny]]
> ![[SRD-corsola-ShuffleToken.png|wsmall]]


*Coral Pokemon*
*People and Pokemon build their communities on top of reefs of these creatures which shine with seven colors in sunlight. Their corals have healing qualities and their presence wards against disasters.*

**DexID**:: 0222
**Name**:: Corsola
**Type**:: Water / Rock
**Abilities**:: [[SRD-Hustle|Hustle]] / [[SRD-Natural Cure|Natural Cure]] ([[SRD-Regenerator|Regenerator]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 2'0" / 0.6m
**Weight**: 11.0lbs / 5.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Corsola.md"
flatten moves as T
where file.path = this.file.path
```
