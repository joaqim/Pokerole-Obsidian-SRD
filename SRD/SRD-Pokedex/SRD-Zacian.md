---
Ability1: Intrepid Sword
Ability2: ''
BookSprite: SRD-zacian-BookSprite.png
BoxSprite: SRD-zacian-BoxSprite.png
DexCategory: No Data
DexDescription: There is a legend of a heroine who through sheer might wielded the
  blade of heroes and vanquished a great evil away.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Zacian (Crown Form)]]'
GenderType: N
Height:
  Feet: 9.2
  Meters: 2.8
HiddenAbility: ''
HomeSprite: SRD-zacian-HomeSprite.png
Image: zacian.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Sacred Sword|Sacred Sword]]'
- - Master
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Master
  - '[[SRD-Howl|Howl]]'
- - Master
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[SRD-Bite|Bite]]'
- - Master
  - '[[SRD-Slash|Slash]]'
- - Master
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Master
  - '[[SRD-Iron Head|Iron Head]]'
- - Master
  - '[[SRD-Laser Focus|Laser Focus]]'
- - Master
  - '[[SRD-Crunch|Crunch]]'
- - Master
  - '[[SRD-Moonblast|Moonblast]]'
- - Master
  - '[[SRD-Close Combat|Close Combat]]'
- - Master
  - '[[SRD-Giga Impact|Giga Impact]]'
- - Master
  - '[[SRD-Air Slash|Air Slash]]'
- - Master
  - '[[SRD-Psycho Cut|Psycho Cut]]'
- - Master
  - '[[SRD-Solar Beam|Solar Beam]]'
Number: 888
ShuffleToken: SRD-zacian-ShuffleToken.png
Type1: Fairy
Type2: ''
Weight:
  Kilograms: 110.0
  Pounds: 242.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-zacian-BookSprite.png|wsmall]]
> ![[SRD-zacian-HomeSprite.png]]
> ![[SRD-zacian-BoxSprite.png|htiny]]
> ![[SRD-zacian-ShuffleToken.png|wsmall]]


*No Data*
*There is a legend of a heroine who through sheer might wielded the blade of heroes and vanquished a great evil away.*

**DexID**:: 0888
**Name**:: Zacian
**Type**:: Fairy
**Abilities**:: [[SRD-Intrepid Sword|Intrepid Sword]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 7)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::5)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 9'2" / 2.8m
**Weight**: 242.5lbs / 110.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon                     | Kind   |
|:----------|:----------------------------|:-------|
| To        | [[SRD-Zacian (Crown Form)]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Zacian.md"
flatten moves as T
where file.path = this.file.path
```
