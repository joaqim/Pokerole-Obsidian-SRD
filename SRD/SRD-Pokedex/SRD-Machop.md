---
Ability1: Guts
Ability2: No Guard
BookSprite: SRD-machop-BookSprite.png
BoxSprite: SRD-machop-BoxSprite.png
DexCategory: Superpower Pokemon
DexDescription: It lives in mountains, training its fists against strong rocks , lifting
  boulders and hurling Rock Pokemon around to build stronger muscles. Even with its
  small size, it can compete against expert humans and win.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Machoke]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Steadfast
HomeSprite: SRD-machop-HomeSprite.png
Image: machop.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Low Kick|Low Kick]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Karate Chop|Karate Chop]]'
- - Beginner
  - '[[SRD-Foresight|Foresight]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Low Sweep|Low Sweep]]'
- - Amateur
  - '[[SRD-Knock Off|Knock Off]]'
- - Amateur
  - '[[SRD-Seismic Toss|Seismic Toss]]'
- - Amateur
  - '[[SRD-Revenge|Revenge]]'
- - Amateur
  - '[[SRD-Vital Throw|Vital Throw]]'
- - Amateur
  - '[[SRD-Dual Chop|Dual Chop]]'
- - Amateur
  - '[[SRD-Submission|Submission]]'
- - Amateur
  - '[[SRD-Wake-Up Slap|Wake-Up Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bulk Up|Bulk Up]]'
- - Ace
  - '[[SRD-Cross Chop|Cross Chop]]'
- - Ace
  - '[[SRD-Scary Face|Scary Face]]'
- - Ace
  - '[[SRD-Dynamic Punch|Dynamic Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Meditate|Meditate]]'
- - Pro
  - '[[SRD-Bullet Punch|Bullet Punch]]'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
Number: 66
ShuffleToken: SRD-machop-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 19.5
  Pounds: 43.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-machop-BookSprite.png|wsmall]]
> ![[SRD-machop-HomeSprite.png]]
> ![[SRD-machop-BoxSprite.png|htiny]]
> ![[SRD-machop-ShuffleToken.png|wsmall]]


*Superpower Pokemon*
*It lives in mountains, training its fists against strong rocks , lifting boulders and hurling Rock Pokemon around to build stronger muscles. Even with its small size, it can compete against expert humans and win.*

**DexID**:: 0066
**Name**:: Machop
**Type**:: Fighting
**Abilities**:: [[SRD-Guts|Guts]] / [[SRD-No Guard|No Guard]] ([[SRD-Steadfast|Steadfast]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'6" / 0.8m
**Weight**: 43.0lbs / 19.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Machoke]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Machop.md"
flatten moves as T
where file.path = this.file.path
```
