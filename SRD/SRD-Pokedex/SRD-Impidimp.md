---
Ability1: Prankster
Ability2: Frisk
BookSprite: SRD-impidimp-BookSprite.png
BoxSprite: SRD-impidimp-BoxSprite.png
DexCategory: Wily Pokemon
DexDescription: "Through its nose, it sucks in the dark emanations produced by people\
  \ and Pokemon when they feel annoyed. It thrives off this negative energy. They\
  \ love to take things that don\u2019t belong to them."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Morgrem]]'
  Speed: Medium
GenderType: M
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Pickpocket
HomeSprite: SRD-impidimp-HomeSprite.png
Image: impidimp.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Fake Out|Fake Out]]'
- - Starter
  - '[[SRD-Confide|Confide]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Flatter|Flatter]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fake Tears|Fake Tears]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Torment|Torment]]'
- - Amateur
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - Ace
  - '[[SRD-Foul Play|Foul Play]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Leech Life|Leech Life]]'
- - Pro
  - '[[SRD-Taunt|Taunt]]'
- - Pro
  - '[[SRD-Trick|Trick]]'
Number: 859
ShuffleToken: SRD-impidimp-ShuffleToken.png
Type1: Dark
Type2: Fairy
Weight:
  Kilograms: 5.5
  Pounds: 12.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-impidimp-BookSprite.png|wsmall]]
> ![[SRD-impidimp-HomeSprite.png]]
> ![[SRD-impidimp-BoxSprite.png|htiny]]
> ![[SRD-impidimp-ShuffleToken.png|wsmall]]


*Wily Pokemon*
*Through its nose, it sucks in the dark emanations produced by people and Pokemon when they feel annoyed. It thrives off this negative energy. They love to take things that don’t belong to them.*

**DexID**:: 0859
**Name**:: Impidimp
**Type**:: Dark / Fairy
**Abilities**:: [[SRD-Prankster|Prankster]] / [[SRD-Frisk|Frisk]] ([[SRD-Pickpocket|Pickpocket]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 12.1lbs / 5.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Morgrem]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Impidimp.md"
flatten moves as T
where file.path = this.file.path
```
