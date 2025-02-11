---
Ability1: Guts
Ability2: ''
BookSprite: SRD-swellow-BookSprite.png
BoxSprite: SRD-swellow-BoxSprite.png
DexCategory: Swallow Pokemon
DexDescription: "They are vain Pokemon, acting with grace and elegance. Swellows are\
  \ seen circling the skies looking for prey. They can be incredibly fast. If two\
  \ Swellows meet, they will clean each other\u2019s wings as a sign of peace."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Taillow]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Scrappy
HomeSprite: SRD-swellow-HomeSprite.png
Image: swellow.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Peck|Peck]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Pluck|Pluck]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Double Team|Double Team]]'
- - Amateur
  - '[[SRD-Wing Attack|Wing Attack]]'
- - Amateur
  - '[[SRD-Endeavor|Endeavor]]'
- - Amateur
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Amateur
  - '[[SRD-Reversal|Reversal]]'
- - Amateur
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Air Slash|Air Slash]]'
- - Ace
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Ace
  - '[[SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Refresh|Refresh]]'
- - Pro
  - '[[SRD-Sky Attack|Sky Attack]]'
- - Pro
  - '[[SRD-Roost|Roost]]'
Number: 277
ShuffleToken: SRD-swellow-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 19.8
  Pounds: 43.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-swellow-BookSprite.png|wsmall]]
> ![[SRD-swellow-HomeSprite.png]]
> ![[SRD-swellow-BoxSprite.png|htiny]]
> ![[SRD-swellow-ShuffleToken.png|wsmall]]


*Swallow Pokemon*
*They are vain Pokemon, acting with grace and elegance. Swellows are seen circling the skies looking for prey. They can be incredibly fast. If two Swellows meet, they will clean each other’s wings as a sign of peace.*

**DexID**:: 0277
**Name**:: Swellow
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Guts|Guts]] ([[SRD-Scrappy|Scrappy]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'3" / 0.7m
**Weight**: 43.7lbs / 19.8kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Taillow]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Swellow.md"
flatten moves as T
where file.path = this.file.path
```
