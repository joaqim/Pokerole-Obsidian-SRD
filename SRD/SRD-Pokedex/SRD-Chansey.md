---
Ability1: Natural Cure
Ability2: Serene Grace
BookSprite: SRD-chansey-BookSprite.png
BoxSprite: SRD-chansey-BoxSprite.png
DexCategory: Egg Pokemon
DexDescription: "There are only females in this species. Chansey lays a nutritive\
  \ egg every day. These eggs are fed to the sick to give them strength. It is a loving\
  \ and smart Pokemon, but it\u2019s pretty rare and elusive in the wild."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Oval Stone
  Kind: Level
  Pokemon: '[[SRD-Happiny]]'
- Evolves: To
  Kind: Stat
  Pokemon: '[[SRD-Blissey]]'
  Stat: Happiness
  Value: 5
GenderType: F
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Healer
HomeSprite: SRD-chansey-HomeSprite.png
Image: chansey.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Defense Curl|Defense Curl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Refresh|Refresh]]'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Soft Boiled|Soft Boiled]]'
- - Beginner
  - '[[SRD-Double Slap|Double Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Amateur
  - '[[SRD-Bestow|Bestow]]'
- - Amateur
  - '[[SRD-Minimize|Minimize]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Sing|Sing]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Fling|Fling]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Egg Bomb|Egg Bomb]]'
- - Ace
  - '[[SRD-Light Screen|Light Screen]]'
- - Ace
  - '[[SRD-Healing Wish|Healing Wish]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Heal Bell|Heal Bell]]'
- - Pro
  - '[[SRD-Seismic Toss|Seismic Toss]]'
- - Pro
  - '[[SRD-Present|Present]]'
Number: 113
ShuffleToken: SRD-chansey-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 34.6
  Pounds: 76.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-chansey-BookSprite.png|wsmall]]
> ![[SRD-chansey-HomeSprite.png]]
> ![[SRD-chansey-BoxSprite.png|htiny]]
> ![[SRD-chansey-ShuffleToken.png|wsmall]]


*Egg Pokemon*
*There are only females in this species. Chansey lays a nutritive egg every day. These eggs are fed to the sick to give them strength. It is a loving and smart Pokemon, but it’s pretty rare and elusive in the wild.*

**DexID**:: 0113
**Name**:: Chansey
**Type**:: Normal
**Abilities**:: [[SRD-Natural Cure|Natural Cure]] / [[SRD-Serene Grace|Serene Grace]] ([[SRD-Healer|Healer]])
**Base HP**:: 12

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::2)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::2)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'6" / 1.1m
**Weight**: 76.3lbs / 34.6kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Item       | Stat      | Value   |
|:----------|:----------------|:-------|:-----------|:----------|:--------|
| From      | [[SRD-Happiny]] | Level  | Oval Stone |           |         |
| To        | [[SRD-Blissey]] | Stat   |            | Happiness | 5.0     |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Chansey.md"
flatten moves as T
where file.path = this.file.path
```
