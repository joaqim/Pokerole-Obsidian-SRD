---
Ability1: Intimidate
Ability2: Anger Point
BookSprite: SRD-tauros-BookSprite.png
BoxSprite: SRD-tauros-BoxSprite.png
DexCategory: Wild Bull Pokemon
DexDescription: "This is a Male species. They travel in herds around the plains and\
  \ fight each other by locking horns. The herd\u2019s protector takes pride in its\
  \ battle-scarred horns. Miltank is the female of this species."
EventAbilities: ''
Evolutions: []
GenderType: M
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Sheer Force
HomeSprite: SRD-tauros-HomeSprite.png
Image: tauros.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rage|Rage]]'
- - Beginner
  - '[[SRD-Horn Attack|Horn Attack]]'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Rest|Rest]]'
- - Amateur
  - '[[SRD-Payback|Payback]]'
- - Amateur
  - '[[SRD-Work Up|Work Up]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Swagger|Swagger]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Giga Impact|Giga Impact]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Smart Strike|Smart Strike]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
- - Pro
  - '[[SRD-Sleep Talk|Sleep Talk]]'
Number: 128
ShuffleToken: SRD-tauros-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 88.4
  Pounds: 194.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tauros-BookSprite.png|wsmall]]
> ![[SRD-tauros-HomeSprite.png]]
> ![[SRD-tauros-BoxSprite.png|htiny]]
> ![[SRD-tauros-ShuffleToken.png|wsmall]]


*Wild Bull Pokemon*
*This is a Male species. They travel in herds around the plains and fight each other by locking horns. The herd’s protector takes pride in its battle-scarred horns. Miltank is the female of this species.*

**DexID**:: 0128
**Name**:: Tauros
**Type**:: Normal
**Abilities**:: [[SRD-Intimidate|Intimidate]] / [[SRD-Anger Point|Anger Point]] ([[SRD-Sheer Force|Sheer Force]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'6" / 1.4m
**Weight**: 194.9lbs / 88.4kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Tauros.md"
flatten moves as T
where file.path = this.file.path
```
