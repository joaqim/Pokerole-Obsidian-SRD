---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-tepig-BookSprite.png
BoxSprite: SRD-tepig-BoxSprite.png
DexCategory: Fire Pig Pokemon
DexDescription: It blows fire through its nose. When it catches a cold, the fire becomes
  pitch-black smoke instead. Tepig loves to eat roasted berries and its keen sense
  of smell allows it to find them easily.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Pignite]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Thick Fat
HomeSprite: SRD-tepig-HomeSprite.png
Image: tepig.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Amateur
  - '[[SRD-Smog|Smog]]'
- - Amateur
  - '[[SRD-Rollout|Rollout]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Heat Crash|Heat Crash]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Ace
  - '[[SRD-Head Smash|Head Smash]]'
- - Ace
  - '[[SRD-Roar|Roar]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fire Pledge|Fire Pledge]]'
- - Pro
  - '[[SRD-Body Slam|Body Slam]]'
- - Pro
  - '[[SRD-Sucker Punch|Sucker Punch]]'
Number: 498
ShuffleToken: SRD-tepig-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 9.9
  Pounds: 21.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tepig-BookSprite.png|wsmall]]
> ![[SRD-tepig-HomeSprite.png]]
> ![[SRD-tepig-BoxSprite.png|htiny]]
> ![[SRD-tepig-ShuffleToken.png|wsmall]]


*Fire Pig Pokemon*
*It blows fire through its nose. When it catches a cold, the fire becomes pitch-black smoke instead. Tepig loves to eat roasted berries and its keen sense of smell allows it to find them easily.*

**DexID**:: 0498
**Name**:: Tepig
**Type**:: Fire
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Thick Fat|Thick Fat]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 21.8lbs / 9.9kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Pignite]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Tepig.md"
flatten moves as T
where file.path = this.file.path
```
