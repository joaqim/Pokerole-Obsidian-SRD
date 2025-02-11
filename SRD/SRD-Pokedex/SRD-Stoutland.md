---
Ability1: Intimidate
Ability2: Sand Rush
BookSprite: SRD-stoutland-BookSprite.png
BoxSprite: SRD-stoutland-BoxSprite.png
DexCategory: Big-Hearted Pokemon
DexDescription: For many years this Pokemon has helped with rescue missions in hostile
  places. Its outer coat is hard on the exterior but soft and silky on the inside.
  They keep people safe and warm while help is on the way.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Herdier]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Scrappy
HomeSprite: SRD-stoutland-HomeSprite.png
Image: stoutland.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Work Up|Work Up]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Retaliate|Retaliate]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[SRD-Giga Impact|Giga Impact]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Psychic Fangs|Psychic Fangs]]'
- - Pro
  - '[[SRD-Iron Head|Iron Head]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
Number: 508
ShuffleToken: SRD-stoutland-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 61.0
  Pounds: 134.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-stoutland-BookSprite.png|wsmall]]
> ![[SRD-stoutland-HomeSprite.png]]
> ![[SRD-stoutland-BoxSprite.png|htiny]]
> ![[SRD-stoutland-ShuffleToken.png|wsmall]]


*Big-Hearted Pokemon*
*For many years this Pokemon has helped with rescue missions in hostile places. Its outer coat is hard on the exterior but soft and silky on the inside. They keep people safe and warm while help is on the way.*

**DexID**:: 0508
**Name**:: Stoutland
**Type**:: Normal
**Abilities**:: [[SRD-Intimidate|Intimidate]] / [[SRD-Sand Rush|Sand Rush]] ([[SRD-Scrappy|Scrappy]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 134.5lbs / 61.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Herdier]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Stoutland.md"
flatten moves as T
where file.path = this.file.path
```
