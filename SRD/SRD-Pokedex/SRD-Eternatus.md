---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-eternatus-BookSprite.png
BoxSprite: SRD-eternatus-BoxSprite.png
DexCategory: No Data
DexDescription: A large meteorite fell on the Galar region 20, 000 years ago, ever
  since this happened a power surge has been causing Pokemon to grow gigantic, this
  phenomenon is happening more in recent years.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 65.6
  Meters: 20.0
HiddenAbility: ''
HomeSprite: SRD-eternatus-HomeSprite.png
Image: eternatus.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Poison Tail|Poison Tail]]'
- - Master
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Master
  - '[[SRD-Dragon Tail|Dragon Tail]]'
- - Master
  - '[[SRD-Agility|Agility]]'
- - Master
  - '[[SRD-Toxic|Toxic]]'
- - Master
  - '[[SRD-Venoshock|Venoshock]]'
- - Master
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Master
  - '[[SRD-Cross Poison|Cross Poison]]'
- - Master
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Master
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Master
  - '[[SRD-Dynamax Cannon|Dynamax Cannon]]'
- - Master
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Master
  - '[[SRD-Recover|Recover]]'
- - Master
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Master
  - '[[SRD-Eternabeam|Eternabeam]]'
- - Master
  - '[[SRD-Light Screen|Light Screen]]'
- - Master
  - '[[SRD-Reflect|Reflect]]'
- - Master
  - '[[SRD-Protect|Protect]]'
Number: 890
ShuffleToken: SRD-eternatus-ShuffleToken.png
Type1: Poison
Type2: Dragon
Weight:
  Kilograms: 950.0
  Pounds: 2094.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-eternatus-BookSprite.png|wsmall]]
> ![[SRD-eternatus-HomeSprite.png]]
> ![[SRD-eternatus-BoxSprite.png|htiny]]
> ![[SRD-eternatus-ShuffleToken.png|wsmall]]


*No Data*
*A large meteorite fell on the Galar region 20, 000 years ago, ever since this happened a power surge has been causing Pokemon to grow gigantic, this phenomenon is happening more in recent years.*

**DexID**:: 0890
**Name**:: Eternatus
**Type**:: Poison / Dragon
**Abilities**:: [[SRD-Pressure|Pressure]]
**Base HP**:: 10

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 7)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::8)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 65'6" / 20.0m
**Weight**: 2094.4lbs / 950.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Eternatus.md"
flatten moves as T
where file.path = this.file.path
```
