---
Ability1: Clear Body
Ability2: ''
BookSprite: SRD-regice-BookSprite.png
BoxSprite: SRD-regice-BoxSprite.png
DexCategory: No Data
DexDescription: "It is said to be indistinguishable from a gigantic iceberg. Its myth\
  \ says its body can\u2019t be melted even if submerged in magma. Regice could freeze\
  \ the air to bring a new ice age."
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: Ice Body
HomeSprite: SRD-regice-HomeSprite.png
Image: regice.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Stomp|Stomp]]'
- - Master
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Master
  - '[[SRD-Charge Beam|Charge Beam]]'
- - Master
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Master
  - '[[SRD-Curse|Curse]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Amnesia|Amnesia]]'
- - Master
  - '[[SRD-Ice Beam|Ice Beam]]'
- - Master
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Master
  - '[[SRD-Lock-On|Lock-On]]'
- - Master
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - Master
  - '[[SRD-Superpower|Superpower]]'
- - Master
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Master
  - '[[SRD-Explosion|Explosion]]'
- - Master
  - '[[SRD-Mimic|Mimic]]'
- - Master
  - '[[SRD-Avalanche|Avalanche]]'
- - Master
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Master
  - '[[SRD-Aurora Veil|Aurora Veil]]'
Number: 378
ShuffleToken: SRD-regice-ShuffleToken.png
Type1: Ice
Type2: ''
Weight:
  Kilograms: 175.0
  Pounds: 385.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-regice-BookSprite.png|wsmall]]
> ![[SRD-regice-HomeSprite.png]]
> ![[SRD-regice-BoxSprite.png|htiny]]
> ![[SRD-regice-ShuffleToken.png|wsmall]]


*No Data*
*It is said to be indistinguishable from a gigantic iceberg. Its myth says its body can’t be melted even if submerged in magma. Regice could freeze the air to bring a new ice age.*

**DexID**:: 0378
**Name**:: Regice
**Type**:: Ice
**Abilities**:: [[SRD-Clear Body|Clear Body]] ([[SRD-Ice Body|Ice Body]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 4)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::10)/(MaxInsight::10)     |

**Height**: 5'9" / 1.8m
**Weight**: 385.8lbs / 175.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Regice.md"
flatten moves as T
where file.path = this.file.path
```
