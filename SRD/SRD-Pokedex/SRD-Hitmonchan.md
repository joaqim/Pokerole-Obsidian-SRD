---
Ability1: Keen Eye
Ability2: Iron Fist
BookSprite: SRD-hitmonchan-BookSprite.png
BoxSprite: SRD-hitmonchan-BoxSprite.png
DexCategory: Punching Pokemon
DexDescription: "It specializes in punching as fast as it can. Using a corkscrew motion,\
  \ it can even drill through concrete with it\u2019s bare hands. This Pokemon takes\
  \ its training very seriously. It\u2019s very rare to see one in the wild."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Stat
  Pokemon: '[[SRD-Tyrogue]]'
  Stat: Vitality
  Value: -1
GenderType: M
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Inner Focus
HomeSprite: SRD-hitmonchan-HomeSprite.png
Image: hitmonchan.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Revenge|Revenge]]'
- - Starter
  - '[[SRD-Comet Punch|Comet Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Agility|Agility]]'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - Beginner
  - '[[SRD-Mach Punch|Mach Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bullet Punch|Bullet Punch]]'
- - Amateur
  - '[[SRD-Feint|Feint]]'
- - Amateur
  - '[[SRD-Vacuum Wave|Vacuum Wave]]'
- - Amateur
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Amateur
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Amateur
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Amateur
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Amateur
  - '[[SRD-Sky Uppercut|Sky Uppercut]]'
- - Amateur
  - '[[SRD-Mega Punch|Mega Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Detect|Detect]]'
- - Ace
  - '[[SRD-Focus Punch|Focus Punch]]'
- - Ace
  - '[[SRD-Counter|Counter]]'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Pro
  - '[[SRD-High Jump Kick|High Jump Kick]]'
Number: 107
ShuffleToken: SRD-hitmonchan-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 50.2
  Pounds: 110.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-hitmonchan-BookSprite.png|wsmall]]
> ![[SRD-hitmonchan-HomeSprite.png]]
> ![[SRD-hitmonchan-BoxSprite.png|htiny]]
> ![[SRD-hitmonchan-ShuffleToken.png|wsmall]]


*Punching Pokemon*
*It specializes in punching as fast as it can. Using a corkscrew motion, it can even drill through concrete with it’s bare hands. This Pokemon takes its training very seriously. It’s very rare to see one in the wild.*

**DexID**:: 0107
**Name**:: Hitmonchan
**Type**:: Fighting
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Iron Fist|Iron Fist]] ([[SRD-Inner Focus|Inner Focus]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'6" / 1.4m
**Weight**: 110.7lbs / 50.2kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Stat     |   Value |
|:----------|:----------------|:-------|:---------|--------:|
| From      | [[SRD-Tyrogue]] | Stat   | Vitality |      -1 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Hitmonchan.md"
flatten moves as T
where file.path = this.file.path
```
