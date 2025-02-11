---
Ability1: Thick Fat
Ability2: Own Tempo
BookSprite: SRD-grumpig-BookSprite.png
BoxSprite: SRD-grumpig-BoxSprite.png
DexCategory: Manipulate Pokemon
DexDescription: Grumpigs control their foes with their psychic powers amplified by
  the pearls on their head and a hypnotic dance. However, when they use their powers,
  they have a difficult time breathing.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Spoink]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Gluttony
HomeSprite: SRD-grumpig-HomeSprite.png
Image: grumpig.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Splash|Splash]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Belch|Belch]]'
- - Beginner
  - '[[SRD-Psywave|Psywave]]'
- - Beginner
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Psych Up|Psych Up]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Magic Coat|Magic Coat]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Rest|Rest]]'
- - Amateur
  - '[[SRD-Snore|Snore]]'
- - Amateur
  - '[[SRD-Teeter Dance|Teeter Dance]]'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psyshock|Psyshock]]'
- - Ace
  - '[[SRD-Payback|Payback]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Bounce|Bounce]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Pro
  - '[[SRD-Future Sight|Future Sight]]'
- - Pro
  - '[[SRD-Trick|Trick]]'
Number: 326
ShuffleToken: SRD-grumpig-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 71.5
  Pounds: 157.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-grumpig-BookSprite.png|wsmall]]
> ![[SRD-grumpig-HomeSprite.png]]
> ![[SRD-grumpig-BoxSprite.png|htiny]]
> ![[SRD-grumpig-ShuffleToken.png|wsmall]]


*Manipulate Pokemon*
*Grumpigs control their foes with their psychic powers amplified by the pearls on their head and a hypnotic dance. However, when they use their powers, they have a difficult time breathing.*

**DexID**:: 0326
**Name**:: Grumpig
**Type**:: Psychic
**Abilities**:: [[SRD-Thick Fat|Thick Fat]] / [[SRD-Own Tempo|Own Tempo]] ([[SRD-Gluttony|Gluttony]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'0" / 0.9m
**Weight**: 157.6lbs / 71.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Spoink]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Grumpig.md"
flatten moves as T
where file.path = this.file.path
```
