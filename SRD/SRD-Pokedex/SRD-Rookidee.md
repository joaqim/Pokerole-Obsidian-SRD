---
Ability1: Keen Eye
Ability2: Unnerve
BookSprite: SRD-rookidee-BookSprite.png
BoxSprite: SRD-rookidee-BoxSprite.png
DexCategory: Tiny Bird Pokemon
DexDescription: "Feisty little creatures, Rookidee are know for challenging foes much\
  \ larger than themselves, and even if they are defeated they don\u2019t give up\
  \ and try again later. They use their small size as an advantage."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Corvisquire]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: Big Pecks
HomeSprite: SRD-rookidee-HomeSprite.png
Image: rookidee.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Power Trip|Power Trip]]'
- - Beginner
  - '[[SRD-Hone Claws|Hone Claws]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Pluck|Pluck]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Drill Peck|Drill Peck]]'
- - Ace
  - '[[SRD-Swagger|Swagger]]'
- - Ace
  - '[[SRD-Brave Bird|Brave Bird]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Spite|Spite]]'
- - Pro
  - '[[SRD-Defog|Defog]]'
- - Pro
  - '[[SRD-Sand Attack|Sand Attack]]'
Number: 821
ShuffleToken: SRD-rookidee-ShuffleToken.png
Type1: Flying
Type2: ''
Weight:
  Kilograms: 1.8
  Pounds: 4.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-rookidee-BookSprite.png|wsmall]]
> ![[SRD-rookidee-HomeSprite.png]]
> ![[SRD-rookidee-BoxSprite.png|htiny]]
> ![[SRD-rookidee-ShuffleToken.png|wsmall]]


*Tiny Bird Pokemon*
*Feisty little creatures, Rookidee are know for challenging foes much larger than themselves, and even if they are defeated they don’t give up and try again later. They use their small size as an advantage.*

**DexID**:: 0821
**Name**:: Rookidee
**Type**:: Flying
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Unnerve|Unnerve]] ([[SRD-Big Pecks|Big Pecks]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 0'7" / 0.2m
**Weight**: 4.0lbs / 1.8kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon             | Kind   | Speed   |
|:----------|:--------------------|:-------|:--------|
| To        | [[SRD-Corvisquire]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Rookidee.md"
flatten moves as T
where file.path = this.file.path
```
