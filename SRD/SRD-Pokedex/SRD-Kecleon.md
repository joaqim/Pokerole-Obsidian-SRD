---
Ability1: Color Change
Ability2: ''
BookSprite: SRD-kecleon-BookSprite.png
BoxSprite: SRD-kecleon-BoxSprite.png
DexCategory: Color Swap Pokemon
DexDescription: "They are able to change their colors to blend with their surroundings.\
  \ The only part of its body that can\u2019t change is the red zigzag line on its\
  \ belly. Kecleon is very sneaky, smart and kind of insolent."
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Protean
HomeSprite: SRD-kecleon-HomeSprite.png
Image: kecleon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Thief|Thief]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Lick|Lick]]'
- - Beginner
  - '[[SRD-Scratch|Scratch]]'
- - Beginner
  - '[[SRD-Bind|Bind]]'
- - Beginner
  - '[[SRD-Feint|Feint]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Camouflage|Camouflage]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Substitute|Substitute]]'
- - Ace
  - '[[SRD-Shadow Claw|Shadow Claw]]'
- - Ace
  - '[[SRD-Synchronoise|Synchronoise]]'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Snatch|Snatch]]'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Trick|Trick]]'
Number: 352
ShuffleToken: SRD-kecleon-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 22.0
  Pounds: 48.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-kecleon-BookSprite.png|wsmall]]
> ![[SRD-kecleon-HomeSprite.png]]
> ![[SRD-kecleon-BoxSprite.png|htiny]]
> ![[SRD-kecleon-ShuffleToken.png|wsmall]]


*Color Swap Pokemon*
*They are able to change their colors to blend with their surroundings. The only part of its body that can’t change is the red zigzag line on its belly. Kecleon is very sneaky, smart and kind of insolent.*

**DexID**:: 0352
**Name**:: Kecleon
**Type**:: Normal
**Abilities**:: [[SRD-Color Change|Color Change]] ([[SRD-Protean|Protean]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 3'3" / 1.0m
**Weight**: 48.5lbs / 22.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Kecleon.md"
flatten moves as T
where file.path = this.file.path
```
