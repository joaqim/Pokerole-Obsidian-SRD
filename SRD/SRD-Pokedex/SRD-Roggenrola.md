---
Ability1: Sturdy
Ability2: Weak Armor
BookSprite: SRD-roggenrola-BookSprite.png
BoxSprite: SRD-roggenrola-BoxSprite.png
DexCategory: Mantle Pokemon
DexDescription: "It is made from compressed rock, making it\u2019s body almost as\
  \ hard as steel. It is blind, what looks like it\u2019s eye is really an ear, for\
  \ this reason it can live in the darkest of caves feeding on rocks to grow stronger."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Boldore]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Sand Force
HomeSprite: SRD-roggenrola-HomeSprite.png
Image: roggenrola.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Headbutt|Headbutt]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Amateur
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Smack Down|Smack Down]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Autotomize|Autotomize]]'
- - Pro
  - '[[SRD-Lock-On|Lock-On]]'
- - Pro
  - '[[SRD-Magnitude|Magnitude]]'
Number: 524
ShuffleToken: SRD-roggenrola-ShuffleToken.png
Type1: Rock
Type2: ''
Weight:
  Kilograms: 18.0
  Pounds: 39.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-roggenrola-BookSprite.png|wsmall]]
> ![[SRD-roggenrola-HomeSprite.png]]
> ![[SRD-roggenrola-BoxSprite.png|htiny]]
> ![[SRD-roggenrola-ShuffleToken.png|wsmall]]


*Mantle Pokemon*
*It is made from compressed rock, making it’s body almost as hard as steel. It is blind, what looks like it’s eye is really an ear, for this reason it can live in the darkest of caves feeding on rocks to grow stronger.*

**DexID**:: 0524
**Name**:: Roggenrola
**Type**:: Rock
**Abilities**:: [[SRD-Sturdy|Sturdy]] / [[SRD-Weak Armor|Weak Armor]] ([[SRD-Sand Force|Sand Force]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 39.7lbs / 18.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Boldore]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Roggenrola.md"
flatten moves as T
where file.path = this.file.path
```
