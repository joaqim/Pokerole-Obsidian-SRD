---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-eelektrik-BookSprite.png
BoxSprite: SRD-eelektrik-BoxSprite.png
DexCategory: EleFish Pokemon
DexDescription: "These Pokemon have a really big appetite. When they spot their prey,\
  \ they coil around it and shock it with their electricity-generating organs, which\
  \ are the yellow circles on it\u2019s skin."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Tynamo]]'
  Speed: Medium
- Evolves: To
  Item: Thunder Stone
  Kind: Stone
  Pokemon: '[[SRD-Eelektross]]'
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: ''
HomeSprite: SRD-eelektrik-HomeSprite.png
Image: eelektrik.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Spark|Spark]]'
- - Starter
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bind|Bind]]'
- - Beginner
  - '[[SRD-Charge Beam|Charge Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Acid|Acid]]'
- - Amateur
  - '[[SRD-Discharge|Discharge]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Thunderbolt|Thunderbolt]]'
- - Amateur
  - '[[SRD-Acid Spray|Acid Spray]]'
- - Amateur
  - '[[SRD-Coil|Coil]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Wild Charge|Wild Charge]]'
- - Ace
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Ace
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Iron Tail|Iron Tail]]'
Number: 603
ShuffleToken: SRD-eelektrik-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 22.0
  Pounds: 48.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-eelektrik-BookSprite.png|wsmall]]
> ![[SRD-eelektrik-HomeSprite.png]]
> ![[SRD-eelektrik-BoxSprite.png|htiny]]
> ![[SRD-eelektrik-ShuffleToken.png|wsmall]]


*EleFish Pokemon*
*These Pokemon have a really big appetite. When they spot their prey, they coil around it and shock it with their electricity-generating organs, which are the yellow circles on it’s skin.*

**DexID**:: 0603
**Name**:: Eelektrik
**Type**:: Electric
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 48.5lbs / 22.0kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon            | Kind   | Speed   | Item          |
|:----------|:-------------------|:-------|:--------|:--------------|
| From      | [[SRD-Tynamo]]     | Level  | Medium  |               |
| To        | [[SRD-Eelektross]] | Stone  |         | Thunder Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Eelektrik.md"
flatten moves as T
where file.path = this.file.path
```
