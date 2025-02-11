---
Ability1: Illuminate
Ability2: Effect Spore
BookSprite: SRD-shiinotic-BookSprite.png
BoxSprite: SRD-shiinotic-BoxSprite.png
DexCategory: Illuminating Pokemon
DexDescription: Forests where Shiinotic live are treacherous to travel. People tell
  stories about strange lights that put others into a deep slumber who are then devoid
  of their energy by these Pokemon, never to return home.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Morelull]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Rain Dish
HomeSprite: SRD-shiinotic-HomeSprite.png
Image: shiinotic.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Flash|Flash]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Moonlight|Moonlight]]'
- - Beginner
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Beginner
  - '[[SRD-Sleep Powder|Sleep Powder]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ingrain|Ingrain]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Amateur
  - '[[SRD-Strength Sap|Strength Sap]]'
- - Amateur
  - '[[SRD-Dream Eater|Dream Eater]]'
- - Amateur
  - '[[SRD-Spotlight|Spotlight]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Spore|Spore]]'
- - Ace
  - '[[SRD-Moonblast|Moonblast]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Pro
  - '[[SRD-Growth|Growth]]'
- - Pro
  - '[[SRD-Light Screen|Light Screen]]'
Number: 756
ShuffleToken: SRD-shiinotic-ShuffleToken.png
Type1: Grass
Type2: Fairy
Weight:
  Kilograms: 11.5
  Pounds: 25.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-shiinotic-BookSprite.png|wsmall]]
> ![[SRD-shiinotic-HomeSprite.png]]
> ![[SRD-shiinotic-BoxSprite.png|htiny]]
> ![[SRD-shiinotic-ShuffleToken.png|wsmall]]


*Illuminating Pokemon*
*Forests where Shiinotic live are treacherous to travel. People tell stories about strange lights that put others into a deep slumber who are then devoid of their energy by these Pokemon, never to return home.*

**DexID**:: 0756
**Name**:: Shiinotic
**Type**:: Grass / Fairy
**Abilities**:: [[SRD-Illuminate|Illuminate]] / [[SRD-Effect Spore|Effect Spore]] ([[SRD-Rain Dish|Rain Dish]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'3" / 1.0m
**Weight**: 25.4lbs / 11.5kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Morelull]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Shiinotic.md"
flatten moves as T
where file.path = this.file.path
```
