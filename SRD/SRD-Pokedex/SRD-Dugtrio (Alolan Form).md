---
Ability1: Sand Veil
Ability2: Tangling Hair
BookSprite: SRD-dugtrio-alolan-form-BookSprite.png
BoxSprite: SRD-dugtrio-alolan-form-BoxSprite.png
DexCategory: Mole Pokemon
DexDescription: "Thanks to its golden mane, this Pokemon has been revered as a feminine\
  \ deity. The triplets groom each other to help keep the hair glossy and dirt-free,\
  \ they don\u2019t like to be petted."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Diglett (Alolan Form)]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Sand Force
HomeSprite: SRD-dugtrio-alolan-form-HomeSprite.png
Image: dugtrio-alolan-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Starter
  - '[[SRD-Metal Claw|Metal Claw]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - Beginner
  - '[[SRD-Mud Slap|Mud Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rototiller|Rototiller]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - Amateur
  - '[[SRD-Tri Attack|Tri Attack]]'
- - Amateur
  - '[[SRD-Sand Tomb|Sand Tomb]]'
- - Amateur
  - '[[SRD-Magnitude|Magnitude]]'
- - Amateur
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Amateur
  - '[[SRD-Earth Power|Earth Power]]'
- - Amateur
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Iron Head|Iron Head]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Fissure|Fissure]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Pro
  - '[[SRD-Thrash|Thrash]]'
- - Pro
  - '[[SRD-Stone Edge|Stone Edge]]'
Number: 51
ShuffleToken: SRD-dugtrio-alolan-form-ShuffleToken.png
Type1: Ground
Type2: Steel
Weight:
  Kilograms: 66.6
  Pounds: 146.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dugtrio-alolan-form-BookSprite.png|wsmall]]
> ![[SRD-dugtrio-alolan-form-HomeSprite.png]]
> ![[SRD-dugtrio-alolan-form-BoxSprite.png|htiny]]
> ![[SRD-dugtrio-alolan-form-ShuffleToken.png|wsmall]]


*Mole Pokemon*
*Thanks to its golden mane, this Pokemon has been revered as a feminine deity. The triplets groom each other to help keep the hair glossy and dirt-free, they don’t like to be petted.*

**DexID**:: 0051A
**Name**:: Dugtrio (Alolan Form)
**Type**:: Ground / Steel
**Abilities**:: [[SRD-Sand Veil|Sand Veil]] / [[SRD-Tangling Hair|Tangling Hair]] ([[SRD-Sand Force|Sand Force]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'3" / 0.7m
**Weight**: 146.8lbs / 66.6kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                       | Kind   | Speed   |
|:----------|:------------------------------|:-------|:--------|
| From      | [[SRD-Diglett (Alolan Form)]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Dugtrio (Alolan Form).md"
flatten moves as T
where file.path = this.file.path
```
