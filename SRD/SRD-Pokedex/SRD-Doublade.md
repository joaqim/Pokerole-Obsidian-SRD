---
Ability1: No Guard
Ability2: ''
BookSprite: SRD-doublade-BookSprite.png
BoxSprite: SRD-doublade-BoxSprite.png
DexCategory: Sword Pokemon
DexDescription: Both swords share a telepathic link to coordinate attacks and slash
  their enemies to shreds. They feed on the rage of their wielder and promise to make
  him unbeatable at the cost of his flesh and soul.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Honedge]]'
  Speed: Slow
- Evolves: To
  Item: Dusk Stone
  Kind: Stone
  Pokemon: '[[SRD-Aegislash]]'
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: ''
HomeSprite: SRD-doublade-HomeSprite.png
Image: doublade.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Swords Dance|Swords Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Beginner
  - '[[SRD-Metal Sound|Metal Sound]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Autotomize|Autotomize]]'
- - Amateur
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Amateur
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - Amateur
  - '[[SRD-Retaliate|Retaliate]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Night Slash|Night Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[SRD-Power Trick|Power Trick]]'
- - Ace
  - '[[SRD-Iron Head|Iron Head]]'
- - Ace
  - '[[SRD-Sacred Sword|Sacred Sword]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - Pro
  - '[[SRD-Spite|Spite]]'
- - Pro
  - '[[SRD-Wide Guard|Wide Guard]]'
Number: 680
ShuffleToken: SRD-doublade-ShuffleToken.png
Type1: Steel
Type2: Ghost
Weight:
  Kilograms: 4.5
  Pounds: 9.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-doublade-BookSprite.png|wsmall]]
> ![[SRD-doublade-HomeSprite.png]]
> ![[SRD-doublade-BoxSprite.png|htiny]]
> ![[SRD-doublade-ShuffleToken.png|wsmall]]


*Sword Pokemon*
*Both swords share a telepathic link to coordinate attacks and slash their enemies to shreds. They feed on the rage of their wielder and promise to make him unbeatable at the cost of his flesh and soul.*

**DexID**:: 0680
**Name**:: Doublade
**Type**:: Steel / Ghost
**Abilities**:: [[SRD-No Guard|No Guard]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::4)/(MaxVitality::8)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 9.9lbs / 4.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon           | Kind   | Speed   | Item       |
|:----------|:------------------|:-------|:--------|:-----------|
| From      | [[SRD-Honedge]]   | Level  | Slow    |            |
| To        | [[SRD-Aegislash]] | Stone  |         | Dusk Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Doublade.md"
flatten moves as T
where file.path = this.file.path
```
