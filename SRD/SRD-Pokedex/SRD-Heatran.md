---
Ability1: Flash Fire
Ability2: ''
BookSprite: SRD-heatran-BookSprite.png
BoxSprite: SRD-heatran-BoxSprite.png
DexCategory: No Data
DexDescription: An old painting showed a similar Pokemon standing atop of an erupting
  Volcano.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: Flame Body
HomeSprite: SRD-heatran-HomeSprite.png
Image: heatran.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Leer|Leer]]'
- - Master
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Master
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Master
  - '[[SRD-Crunch|Crunch]]'
- - Master
  - '[[SRD-Scary Face|Scary Face]]'
- - Master
  - '[[SRD-Lava Plume|Lava Plume]]'
- - Master
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Master
  - '[[SRD-Iron Head|Iron Head]]'
- - Master
  - '[[SRD-Earth Power|Earth Power]]'
- - Master
  - '[[SRD-Heat Wave|Heat Wave]]'
- - Master
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Master
  - '[[SRD-Magma Storm|Magma Storm]]'
- - Master
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[SRD-Sunny Day|Sunny Day]]'
- - Master
  - '[[SRD-Stomping Tantrum|Stomping Tantrum]]'
- - Master
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Master
  - '[[SRD-Uproar|Uproar]]'
Number: 485
ShuffleToken: SRD-heatran-ShuffleToken.png
Type1: Fire
Type2: Steel
Weight:
  Kilograms: 430.0
  Pounds: 948.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-heatran-BookSprite.png|wsmall]]
> ![[SRD-heatran-HomeSprite.png]]
> ![[SRD-heatran-BoxSprite.png|htiny]]
> ![[SRD-heatran-ShuffleToken.png|wsmall]]


*No Data*
*An old painting showed a similar Pokemon standing atop of an erupting Volcano.*

**DexID**:: 0485
**Name**:: Heatran
**Type**:: Fire / Steel
**Abilities**:: [[SRD-Flash Fire|Flash Fire]] ([[SRD-Flame Body|Flame Body]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 5'6" / 1.7m
**Weight**: 948.0lbs / 430.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Heatran.md"
flatten moves as T
where file.path = this.file.path
```
