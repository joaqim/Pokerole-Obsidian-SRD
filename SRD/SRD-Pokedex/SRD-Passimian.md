---
Ability1: Receiver
Ability2: ''
BookSprite: SRD-passimian-BookSprite.png
BoxSprite: SRD-passimian-BoxSprite.png
DexCategory: Teamwork Pokemon
DexDescription: They live in packs of 20 members, they are all coordinated to pass
  around the food and to defend their nest. Their leader is not the strongest but
  the best teamworker of the pack. A very loyal Pokemon.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: Defiant
HomeSprite: SRD-passimian-HomeSprite.png
Image: passimian.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rock Smash|Rock Smash]]'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Beat Up|Beat Up]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Bestow|Bestow]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - Amateur
  - '[[SRD-Bulk Up|Bulk Up]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - Ace
  - '[[SRD-Giga Impact|Giga Impact]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Seismic Toss|Seismic Toss]]'
- - Pro
  - '[[SRD-Iron Head|Iron Head]]'
- - Pro
  - '[[SRD-Feint|Feint]]'
Number: 766
ShuffleToken: SRD-passimian-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 82.8
  Pounds: 182.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-passimian-BookSprite.png|wsmall]]
> ![[SRD-passimian-HomeSprite.png]]
> ![[SRD-passimian-BoxSprite.png|htiny]]
> ![[SRD-passimian-ShuffleToken.png|wsmall]]


*Teamwork Pokemon*
*They live in packs of 20 members, they are all coordinated to pass around the food and to defend their nest. Their leader is not the strongest but the best teamworker of the pack. A very loyal Pokemon.*

**DexID**:: 0766
**Name**:: Passimian
**Type**:: Fighting
**Abilities**:: [[SRD-Receiver|Receiver]] ([[SRD-Defiant|Defiant]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 6'6" / 2.0m
**Weight**: 182.5lbs / 82.8kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Passimian.md"
flatten moves as T
where file.path = this.file.path
```
