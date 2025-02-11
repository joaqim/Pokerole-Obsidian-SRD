---
Ability1: Pickup
Ability2: Thick Fat
BookSprite: SRD-munchlax-BookSprite.png
BoxSprite: SRD-munchlax-BoxSprite.png
DexCategory: Big Eater Pokemon
DexDescription: A Munchlaxes appetite is never really satisfied, it can eat its weight
  in food and will almost never care about what it is eating. They tend to pick up
  anything that looks edible and save it for later.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Stat
  Pokemon: '[[SRD-Snorlax]]'
  Stat: Happiness
  Value: 4
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Gluttony
HomeSprite: SRD-munchlax-HomeSprite.png
Image: munchlax.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Snatch|Snatch]]'
- - Starter
  - '[[SRD-Lick|Lick]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Metronome|Metronome]]'
- - Beginner
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Beginner
  - '[[SRD-Amnesia|Amnesia]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Stockpile|Stockpile]]'
- - Amateur
  - '[[SRD-Swallow|Swallow]]'
- - Amateur
  - '[[SRD-Rollout|Rollout]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Belly Drum|Belly Drum]]'
- - Ace
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Charm|Charm]]'
- - Pro
  - '[[SRD-Belch|Belch]]'
- - Pro
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
Number: 446
ShuffleToken: SRD-munchlax-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 105.0
  Pounds: 231.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-munchlax-BookSprite.png|wsmall]]
> ![[SRD-munchlax-HomeSprite.png]]
> ![[SRD-munchlax-BoxSprite.png|htiny]]
> ![[SRD-munchlax-ShuffleToken.png|wsmall]]


*Big Eater Pokemon*
*A Munchlaxes appetite is never really satisfied, it can eat its weight in food and will almost never care about what it is eating. They tend to pick up anything that looks edible and save it for later.*

**DexID**:: 0446
**Name**:: Munchlax
**Type**:: Normal
**Abilities**:: [[SRD-Pickup|Pickup]] / [[SRD-Thick Fat|Thick Fat]] ([[SRD-Gluttony|Gluttony]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'0" / 0.6m
**Weight**: 231.5lbs / 105.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Stat      |   Value |
|:----------|:----------------|:-------|:----------|--------:|
| To        | [[SRD-Snorlax]] | Stat   | Happiness |       4 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Munchlax.md"
flatten moves as T
where file.path = this.file.path
```
