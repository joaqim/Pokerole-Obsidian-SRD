---
Ability1: Prankster
Ability2: Frisk
BookSprite: SRD-morgrem-BookSprite.png
BoxSprite: SRD-morgrem-BoxSprite.png
DexCategory: Devious Pokemon
DexDescription: "When it gets down on all fours as if to beg for forgiveness, it\u2019\
  s trying to lure opponents in so that it can stab them with its spear-like hair.\
  \ It lures people into the woods to rob them and get them lost."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Impidimp]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Grimmsnarl]]'
  Speed: Medium
GenderType: M
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Pickpocket
HomeSprite: SRD-morgrem-HomeSprite.png
Image: morgrem.png
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
  - '[[SRD-False Surrender|False Surrender]]'
- - Amateur
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Ace
  - '[[SRD-Foul Play|Foul Play]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Leech Life|Leech Life]]'
- - Pro
  - '[[SRD-Metronome|Metronome]]'
- - Pro
  - '[[SRD-Trick|Trick]]'
Number: 860
ShuffleToken: SRD-morgrem-ShuffleToken.png
Type1: Dark
Type2: Fairy
Weight:
  Kilograms: 12.5
  Pounds: 27.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-morgrem-BookSprite.png|wsmall]]
> ![[SRD-morgrem-HomeSprite.png]]
> ![[SRD-morgrem-BoxSprite.png|htiny]]
> ![[SRD-morgrem-ShuffleToken.png|wsmall]]


*Devious Pokemon*
*When it gets down on all fours as if to beg for forgiveness, it’s trying to lure opponents in so that it can stab them with its spear-like hair. It lures people into the woods to rob them and get them lost.*

**DexID**:: 0860
**Name**:: Morgrem
**Type**:: Dark / Fairy
**Abilities**:: [[SRD-Prankster|Prankster]] / [[SRD-Frisk|Frisk]] ([[SRD-Pickpocket|Pickpocket]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 27.6lbs / 12.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| From      | [[SRD-Impidimp]]   | Level  | Medium  |
| To        | [[SRD-Grimmsnarl]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Morgrem.md"
flatten moves as T
where file.path = this.file.path
```
