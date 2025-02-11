---
Ability1: Battery
Ability2: ''
BookSprite: SRD-charjabug-BookSprite.png
BoxSprite: SRD-charjabug-BoxSprite.png
DexCategory: Battery Pokemon
DexDescription: Whatever this Pokemon eats is transformed to electricity. People often
  use them to power up small appliances in their homes. This Pokemon rarely moves
  since it is preparing to evolve.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Grubbin]]'
  Speed: Fast
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Vikavolt]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: ''
HomeSprite: SRD-charjabug-HomeSprite.png
Image: charjabug.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-String Shot|String Shot]]'
- - Starter
  - '[[SRD-Vice Grip|Vice Grip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Beginner
  - '[[SRD-Bug Bite|Bug Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Charge|Charge]]'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Acrobatics|Acrobatics]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Iron Defense|Iron Defense]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Endure|Endure]]'
- - Pro
  - '[[SRD-Charge Beam|Charge Beam]]'
- - Pro
  - '[[SRD-Electroweb|Electroweb]]'
Number: 737
ShuffleToken: SRD-charjabug-ShuffleToken.png
Type1: Bug
Type2: Electric
Weight:
  Kilograms: 10.5
  Pounds: 23.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-charjabug-BookSprite.png|wsmall]]
> ![[SRD-charjabug-HomeSprite.png]]
> ![[SRD-charjabug-BoxSprite.png|htiny]]
> ![[SRD-charjabug-ShuffleToken.png|wsmall]]


*Battery Pokemon*
*Whatever this Pokemon eats is transformed to electricity. People often use them to power up small appliances in their homes. This Pokemon rarely moves since it is preparing to evolve.*

**DexID**:: 0737
**Name**:: Charjabug
**Type**:: Bug / Electric
**Abilities**:: [[SRD-Battery|Battery]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 1'6" / 0.5m
**Weight**: 23.1lbs / 10.5kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Grubbin]]  | Level  | Fast    |
| To        | [[SRD-Vikavolt]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Charjabug.md"
flatten moves as T
where file.path = this.file.path
```
