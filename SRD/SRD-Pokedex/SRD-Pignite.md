---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-pignite-BookSprite.png
BoxSprite: SRD-pignite-BoxSprite.png
DexCategory: Fire Pig Pokemon
DexDescription: Whatever it eats becomes fuel for the flame on its stomach. When it
  is angered, the intensity of the flame increases. It is not common to see them the
  wild. They are mostly found living in warm places.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Tepig]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Emboar]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Thick Fat
HomeSprite: SRD-pignite-HomeSprite.png
Image: pignite.png
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
- - Beginner
  - '[[SRD-Defense Curl|Defense Curl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Amateur
  - '[[SRD-Arm Thrust|Arm Thrust]]'
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
Number: 499
ShuffleToken: SRD-pignite-ShuffleToken.png
Type1: Fire
Type2: Fighting
Weight:
  Kilograms: 55.5
  Pounds: 122.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pignite-BookSprite.png|wsmall]]
> ![[SRD-pignite-HomeSprite.png]]
> ![[SRD-pignite-BoxSprite.png|htiny]]
> ![[SRD-pignite-ShuffleToken.png|wsmall]]


*Fire Pig Pokemon*
*Whatever it eats becomes fuel for the flame on its stomach. When it is angered, the intensity of the flame increases. It is not common to see them the wild. They are mostly found living in warm places.*

**DexID**:: 0499
**Name**:: Pignite
**Type**:: Fire / Fighting
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Thick Fat|Thick Fat]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 122.4lbs / 55.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Tepig]]  | Level  | Medium  |
| To        | [[SRD-Emboar]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Pignite.md"
flatten moves as T
where file.path = this.file.path
```
