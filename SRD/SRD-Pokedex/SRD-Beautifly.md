---
Ability1: Swarm
Ability2: ''
BookSprite: SRD-beautifly-BookSprite.png
BoxSprite: SRD-beautifly-BoxSprite.png
DexCategory: Butterfly Pokemon
DexDescription: "They can\u2019t resist the pollen of flowers, if you leave one in\
  \ the window, a Beautifly is sure to come. Despite their appearance, they are aggressive,\
  \ they drain living creatures of their fluids just as they do with flowers."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Silcoon]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Rivalry
HomeSprite: SRD-beautifly-HomeSprite.png
Image: beautifly.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Gust|Gust]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Stun Spore|Stun Spore]]'
- - Amateur
  - '[[SRD-Morning Sun|Morning Sun]]'
- - Amateur
  - '[[SRD-Air Cutter|Air Cutter]]'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Amateur
  - '[[SRD-Attract|Attract]]'
- - Amateur
  - '[[SRD-Silver Wind|Silver Wind]]'
- - Amateur
  - '[[SRD-Rage|Rage]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Ace
  - '[[SRD-Quiver Dance|Quiver Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Swift|Swift]]'
- - Pro
  - '[[SRD-Defog|Defog]]'
- - Pro
  - '[[SRD-Captivate|Captivate]]'
Number: 267
ShuffleToken: SRD-beautifly-ShuffleToken.png
Type1: Bug
Type2: Flying
Weight:
  Kilograms: 28.4
  Pounds: 62.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-beautifly-BookSprite.png|wsmall]]
> ![[SRD-beautifly-HomeSprite.png]]
> ![[SRD-beautifly-BoxSprite.png|htiny]]
> ![[SRD-beautifly-ShuffleToken.png|wsmall]]


*Butterfly Pokemon*
*They can’t resist the pollen of flowers, if you leave one in the window, a Beautifly is sure to come. Despite their appearance, they are aggressive, they drain living creatures of their fluids just as they do with flowers.*

**DexID**:: 0267
**Name**:: Beautifly
**Type**:: Bug / Flying
**Abilities**:: [[SRD-Swarm|Swarm]] ([[SRD-Rivalry|Rivalry]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 62.6lbs / 28.4kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Silcoon]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Beautifly.md"
flatten moves as T
where file.path = this.file.path
```
