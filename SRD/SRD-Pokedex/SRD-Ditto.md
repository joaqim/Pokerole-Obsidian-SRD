---
Ability1: Limber
Ability2: ''
BookSprite: SRD-ditto-BookSprite.png
BoxSprite: SRD-ditto-BoxSprite.png
DexCategory: Transform Pokemon
DexDescription: "This Pokemon is quite common but it\u2019s pretty difficult to spot.\
  \ It can transform into any other Pokemon and imitate their behavior. When it sleeps,\
  \ it changes into a stone to avoid being attacked."
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Imposter
HomeSprite: SRD-ditto-HomeSprite.png
Image: ditto.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Transform|Transform]]'
Number: 132
ShuffleToken: SRD-ditto-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 4.0
  Pounds: 8.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-ditto-BookSprite.png|wsmall]]
> ![[SRD-ditto-HomeSprite.png]]
> ![[SRD-ditto-BoxSprite.png|htiny]]
> ![[SRD-ditto-ShuffleToken.png|wsmall]]


*Transform Pokemon*
*This Pokemon is quite common but it’s pretty difficult to spot. It can transform into any other Pokemon and imitate their behavior. When it sleeps, it changes into a stone to avoid being attacked.*

**DexID**:: 0132
**Name**:: Ditto
**Type**:: Normal
**Abilities**:: [[SRD-Limber|Limber]] ([[SRD-Imposter|Imposter]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'0" / 0.3m
**Weight**: 8.8lbs / 4.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Ditto.md"
flatten moves as T
where file.path = this.file.path
```
