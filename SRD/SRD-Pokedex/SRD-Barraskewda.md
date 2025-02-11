---
Ability1: Swift Swim
Ability2: ''
BookSprite: SRD-barraskewda-BookSprite.png
BoxSprite: SRD-barraskewda-BoxSprite.png
DexCategory: Skewer Pokemon
DexDescription: "This Pokemon has a jaw that\u2019s as sharp as a spear and as strong\
  \ as steel. Apparently Barraskewda's flesh is surprisingly tasty, too. When they\
  \ hunt, they have speed burst record of 100 knots."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Arrokuda]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Propeller Tail
HomeSprite: SRD-barraskewda-HomeSprite.png
Image: barraskewda.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Throat Chop|Throat Chop]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Dive|Dive]]'
- - Amateur
  - '[[SRD-Laser Focus|Laser Focus]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Liquidation|Liquidation]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Night Slash|Night Slash]]'
- - Pro
  - '[[SRD-Poison Jab|Poison Jab]]'
- - Pro
  - '[[SRD-Giga Impact|Giga Impact]]'
Number: 847
ShuffleToken: SRD-barraskewda-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 30.0
  Pounds: 66.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-barraskewda-BookSprite.png|wsmall]]
> ![[SRD-barraskewda-HomeSprite.png]]
> ![[SRD-barraskewda-BoxSprite.png|htiny]]
> ![[SRD-barraskewda-ShuffleToken.png|wsmall]]


*Skewer Pokemon*
*This Pokemon has a jaw that’s as sharp as a spear and as strong as steel. Apparently Barraskewda's flesh is surprisingly tasty, too. When they hunt, they have speed burst record of 100 knots.*

**DexID**:: 0847
**Name**:: Barraskewda
**Type**:: Water
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] ([[SRD-Propeller Tail|Propeller Tail]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'3" / 1.3m
**Weight**: 66.1lbs / 30.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Arrokuda]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Barraskewda.md"
flatten moves as T
where file.path = this.file.path
```
