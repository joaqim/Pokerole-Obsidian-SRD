---
Ability1: Defiant
Ability2: Inner Focus
BookSprite: SRD-pawniard-BookSprite.png
BoxSprite: SRD-pawniard-BoxSprite.png
DexCategory: Sharp Blade Pokemon
DexDescription: They live in groups commanded by Bisharp. They cling to their prey
  and inflict damage by sinking their blades. If battling dulls the blades, it sharpens
  them on stones by the river. It takes them years to evolve.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Bisharp]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Pressure
HomeSprite: SRD-pawniard-HomeSprite.png
Image: pawniard.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Torment|Torment]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Embargo|Embargo]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Iron Head|Iron Head]]'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Ace
  - '[[SRD-Guillotine|Guillotine]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Pro
  - '[[SRD-Mean Look|Mean Look]]'
- - Pro
  - '[[SRD-Quick Guard|Quick Guard]]'
Number: 624
ShuffleToken: SRD-pawniard-ShuffleToken.png
Type1: Dark
Type2: Steel
Weight:
  Kilograms: 10.2
  Pounds: 22.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pawniard-BookSprite.png|wsmall]]
> ![[SRD-pawniard-HomeSprite.png]]
> ![[SRD-pawniard-BoxSprite.png|htiny]]
> ![[SRD-pawniard-ShuffleToken.png|wsmall]]


*Sharp Blade Pokemon*
*They live in groups commanded by Bisharp. They cling to their prey and inflict damage by sinking their blades. If battling dulls the blades, it sharpens them on stones by the river. It takes them years to evolve.*

**DexID**:: 0624
**Name**:: Pawniard
**Type**:: Dark / Steel
**Abilities**:: [[SRD-Defiant|Defiant]] / [[SRD-Inner Focus|Inner Focus]] ([[SRD-Pressure|Pressure]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'6" / 0.5m
**Weight**: 22.5lbs / 10.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Bisharp]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Pawniard.md"
flatten moves as T
where file.path = this.file.path
```
