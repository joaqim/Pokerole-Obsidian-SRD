---
Ability1: Hunger Switch
Ability2: ''
BookSprite: SRD-morpeko-BookSprite.png
BoxSprite: SRD-morpeko-BoxSprite.png
DexCategory: Two-Sided Pokemon
DexDescription: "It\u2019s Full-Belly Mode is friendly and playful, it treasures food\
  \ and treats. But intense hunger drives it to extremes of violence, and the electricity\
  \ in its cheek sacs turn into a Dark-type energy"
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: ''
HomeSprite: SRD-morpeko-HomeSprite.png
Image: morpeko.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - Beginner
  - '[[SRD-Power Trip|Power Trip]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Flatter|Flatter]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Torment|Torment]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Aura Wheel|Aura Wheel]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Super Fang|Super Fang]]'
- - Pro
  - '[[SRD-Wild Charge|Wild Charge]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
Number: 877
ShuffleToken: SRD-morpeko-ShuffleToken.png
Type1: Electric
Type2: Dark
Weight:
  Kilograms: 3.0
  Pounds: 6.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-morpeko-BookSprite.png|wsmall]]
> ![[SRD-morpeko-HomeSprite.png]]
> ![[SRD-morpeko-BoxSprite.png|htiny]]
> ![[SRD-morpeko-ShuffleToken.png|wsmall]]


*Two-Sided Pokemon*
*It’s Full-Belly Mode is friendly and playful, it treasures food and treats. But intense hunger drives it to extremes of violence, and the electricity in its cheek sacs turn into a Dark-type energy*

**DexID**:: 0877
**Name**:: Morpeko
**Type**:: Electric / Dark
**Abilities**:: [[SRD-Hunger Switch|Hunger Switch]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'0" / 0.3m
**Weight**: 6.6lbs / 3.0kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Morpeko.md"
flatten moves as T
where file.path = this.file.path
```
