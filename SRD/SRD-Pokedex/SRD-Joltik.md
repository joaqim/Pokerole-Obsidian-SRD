---
Ability1: Compound Eyes
Ability2: Unnerve
BookSprite: SRD-joltik-BookSprite.png
BoxSprite: SRD-joltik-BoxSprite.png
DexCategory: Attaching Pokemon
DexDescription: "Since it can\u2019t generate its own charge, it sticks into larger\
  \ Pokemon and absorbs the static electricity of their fur. In the cities they suck\
  \ electricity from the outlets they find, skyrocketting the power bill."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Galvantula]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 0.3
  Meters: 0.1
HiddenAbility: Swarm
HomeSprite: SRD-joltik-HomeSprite.png
Image: joltik.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-String Shot|String Shot]]'
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Spider Web|Spider Web]]'
- - Beginner
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Amateur
  - '[[SRD-Electroweb|Electroweb]]'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Electro Ball|Electro Ball]]'
- - Amateur
  - '[[SRD-Signal Beam|Signal Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Agility|Agility]]'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Poison Sting|Poison Sting]]'
- - Pro
  - '[[SRD-Bounce|Bounce]]'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
Number: 595
ShuffleToken: SRD-joltik-ShuffleToken.png
Type1: Bug
Type2: Electric
Weight:
  Kilograms: 0.6
  Pounds: 1.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-joltik-BookSprite.png|wsmall]]
> ![[SRD-joltik-HomeSprite.png]]
> ![[SRD-joltik-BoxSprite.png|htiny]]
> ![[SRD-joltik-ShuffleToken.png|wsmall]]


*Attaching Pokemon*
*Since it can’t generate its own charge, it sticks into larger Pokemon and absorbs the static electricity of their fur. In the cities they suck electricity from the outlets they find, skyrocketting the power bill.*

**DexID**:: 0595
**Name**:: Joltik
**Type**:: Bug / Electric
**Abilities**:: [[SRD-Compound Eyes|Compound Eyes]] / [[SRD-Unnerve|Unnerve]] ([[SRD-Swarm|Swarm]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 0'3" / 0.1m
**Weight**: 1.3lbs / 0.6kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| To        | [[SRD-Galvantula]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Joltik.md"
flatten moves as T
where file.path = this.file.path
```
