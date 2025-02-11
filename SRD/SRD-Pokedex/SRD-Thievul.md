---
Ability1: Run Away
Ability2: Unburden
BookSprite: SRD-thievul-BookSprite.png
BoxSprite: SRD-thievul-BoxSprite.png
DexCategory: Fox Pokemon
DexDescription: They have long been hunted down by packs of Boltund because of all
  the trouble they cause in human settlements. They are experts at stealing food and
  Pokemon eggs, never leaving a trace behind.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Nickit]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Stakeout
HomeSprite: SRD-thievul-HomeSprite.png
Image: thievul.png
Legendary: 'No'
Moves:
- - Beginner
  - '[[SRD-Thief|Thief]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Hone Claws|Hone Claws]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Amateur
  - '[[SRD-Beat Up|Beat Up]]'
- - Amateur
  - '[[SRD-Snarl|Snarl]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Tail Slap|Tail Slap]]'
- - Ace
  - '[[SRD-Foul Play|Foul Play]]'
- - Ace
  - '[[SRD-Parting Shot|Parting Shot]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Pro
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - Pro
  - '[[SRD-Acrobatics|Acrobatics]]'
Number: 828
ShuffleToken: SRD-thievul-ShuffleToken.png
Type1: Dark
Type2: ''
Weight:
  Kilograms: 19.9
  Pounds: 43.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-thievul-BookSprite.png|wsmall]]
> ![[SRD-thievul-HomeSprite.png]]
> ![[SRD-thievul-BoxSprite.png|htiny]]
> ![[SRD-thievul-ShuffleToken.png|wsmall]]


*Fox Pokemon*
*They have long been hunted down by packs of Boltund because of all the trouble they cause in human settlements. They are experts at stealing food and Pokemon eggs, never leaving a trace behind.*

**DexID**:: 0828
**Name**:: Thievul
**Type**:: Dark
**Abilities**:: [[SRD-Run Away|Run Away]] / [[SRD-Unburden|Unburden]] ([[SRD-Stakeout|Stakeout]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 43.9lbs / 19.9kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Nickit]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Thievul.md"
flatten moves as T
where file.path = this.file.path
```
