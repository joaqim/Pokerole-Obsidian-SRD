---
Ability1: Run Away
Ability2: Guts
BookSprite: SRD-raticate-BookSprite.png
BoxSprite: SRD-raticate-BoxSprite.png
DexCategory: Mouse Pokemon
DexDescription: Raticate's sturdy fangs grow quickly. To keep them ground down, it
  gnaws on hard materials. It may even chew on the walls of houses. Its has water-proof
  fur, webbed feet and its a capable swimmer.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Rattata]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Hustle
HomeSprite: SRD-raticate-HomeSprite.png
Image: raticate.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Flame Wheel|Flame Wheel]]'
- - Amateur
  - '[[SRD-Hyper Fang|Hyper Fang]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Super Fang|Super Fang]]'
- - Ace
  - '[[SRD-Endeavor|Endeavor]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Pro
  - '[[SRD-Last Resort|Last Resort]]'
- - Pro
  - '[[SRD-Final Gambit|Final Gambit]]'
Number: 20
ShuffleToken: SRD-raticate-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 18.5
  Pounds: 40.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-raticate-BookSprite.png|wsmall]]
> ![[SRD-raticate-HomeSprite.png]]
> ![[SRD-raticate-BoxSprite.png|htiny]]
> ![[SRD-raticate-ShuffleToken.png|wsmall]]


*Mouse Pokemon*
*Raticate's sturdy fangs grow quickly. To keep them ground down, it gnaws on hard materials. It may even chew on the walls of houses. Its has water-proof fur, webbed feet and its a capable swimmer.*

**DexID**:: 0020
**Name**:: Raticate
**Type**:: Normal
**Abilities**:: [[SRD-Run Away|Run Away]] / [[SRD-Guts|Guts]] ([[SRD-Hustle|Hustle]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'3" / 0.7m
**Weight**: 40.8lbs / 18.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Rattata]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Raticate.md"
flatten moves as T
where file.path = this.file.path
```
