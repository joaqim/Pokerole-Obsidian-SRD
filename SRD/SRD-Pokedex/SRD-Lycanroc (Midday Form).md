---
Ability1: Keen Eye
Ability2: Sand Rush
BookSprite: SRD-lycanroc-midday-form-BookSprite.png
BoxSprite: SRD-lycanroc-midday-form-BoxSprite.png
DexCategory: Wolf Pokemon
DexDescription: A well-disciplined Rockruff will evolve at Dawn. This Pokemon is very
  Loyal and trustworthy. It can climb mountains fast and is a quick runner. The rocks
  on its mane are its main weapons.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Rockruff]]'
  Special: Day
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Steadfast
HomeSprite: SRD-lycanroc-midday-form-HomeSprite.png
Image: lycanroc-midday-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Howl|Howl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Accelerock|Accelerock]]'
- - Amateur
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Amateur
  - '[[SRD-Rock Throw|Rock Throw]]'
- - Amateur
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Amateur
  - '[[SRD-Rock Tomb|Rock Tomb]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Rock Climb|Rock Climb]]'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Rock Polish|Rock Polish]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Drill Run|Drill Run]]'
Number: 745
ShuffleToken: SRD-lycanroc-midday-form-ShuffleToken.png
Type1: Rock
Type2: ''
Weight:
  Kilograms: 25.0
  Pounds: 55.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-lycanroc-midday-form-BookSprite.png|wsmall]]
> ![[SRD-lycanroc-midday-form-HomeSprite.png]]
> ![[SRD-lycanroc-midday-form-BoxSprite.png|htiny]]
> ![[SRD-lycanroc-midday-form-ShuffleToken.png|wsmall]]


*Wolf Pokemon*
*A well-disciplined Rockruff will evolve at Dawn. This Pokemon is very Loyal and trustworthy. It can climb mountains fast and is a quick runner. The rocks on its mane are its main weapons.*

**DexID**:: 0745
**Name**:: Lycanroc (Midday Form)
**Type**:: Rock
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Sand Rush|Sand Rush]] ([[SRD-Steadfast|Steadfast]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 55.1lbs / 25.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   | Special   |
|:----------|:-----------------|:-------|:--------|:----------|
| From      | [[SRD-Rockruff]] | Level  | Medium  | Day       |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Lycanroc (Midday Form).md"
flatten moves as T
where file.path = this.file.path
```
