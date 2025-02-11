---
Ability1: Thick Fat
Ability2: Own Tempo
BookSprite: SRD-spoink-BookSprite.png
BoxSprite: SRD-spoink-BoxSprite.png
DexCategory: Bounce Pokemon
DexDescription: "They are always bouncing with their tail. If they ever stop, their\
  \ heart wouldn\u2019t beat anymore. Spoinks balance a pearl from Clamperl on their\
  \ head, if it\u2019s lost, they won\u2019t be able to control their psychic powers."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Grumpig]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Gluttony
HomeSprite: SRD-spoink-HomeSprite.png
Image: spoink.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Splash|Splash]]'
- - '---------------------------'
  - '---------------------------'
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
  - '[[SRD-Role Play|Role Play]]'
- - Pro
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Pro
  - '[[SRD-Extrasensory|Extrasensory]]'
Number: 325
ShuffleToken: SRD-spoink-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 30.6
  Pounds: 67.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-spoink-BookSprite.png|wsmall]]
> ![[SRD-spoink-HomeSprite.png]]
> ![[SRD-spoink-BoxSprite.png|htiny]]
> ![[SRD-spoink-ShuffleToken.png|wsmall]]


*Bounce Pokemon*
*They are always bouncing with their tail. If they ever stop, their heart wouldn’t beat anymore. Spoinks balance a pearl from Clamperl on their head, if it’s lost, they won’t be able to control their psychic powers.*

**DexID**:: 0325
**Name**:: Spoink
**Type**:: Psychic
**Abilities**:: [[SRD-Thick Fat|Thick Fat]] / [[SRD-Own Tempo|Own Tempo]] ([[SRD-Gluttony|Gluttony]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'3" / 0.7m
**Weight**: 67.5lbs / 30.6kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Grumpig]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Spoink.md"
flatten moves as T
where file.path = this.file.path
```
