---
Ability1: Soundproof
Ability2: ''
BookSprite: SRD-whismur-BookSprite.png
BoxSprite: SRD-whismur-BoxSprite.png
DexCategory: Whisper Pokemon
DexDescription: Their timid voice is barely audible, however, if it senses danger,
  they start crying loud enough to deafen anyone nearby. Their own noise scares them
  even more, so they cry harder until their ear covers shut.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Loudred]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Rattled
HomeSprite: SRD-whismur-HomeSprite.png
Image: whismur.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Echoed Voice|Echoed Voice]]'
- - Beginner
  - '[[SRD-Uproar|Uproar]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Astonish|Astonish]]'
- - Amateur
  - '[[SRD-Howl|Howl]]'
- - Amateur
  - '[[SRD-Supersonic|Supersonic]]'
- - Amateur
  - '[[SRD-Stomp|Stomp]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Synchronoise|Synchronoise]]'
- - Ace
  - '[[SRD-Rest|Rest]]'
- - Ace
  - '[[SRD-Sleep Talk|Sleep Talk]]'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
- - Pro
  - '[[SRD-Snore|Snore]]'
Number: 293
ShuffleToken: SRD-whismur-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 16.3
  Pounds: 35.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-whismur-BookSprite.png|wsmall]]
> ![[SRD-whismur-HomeSprite.png]]
> ![[SRD-whismur-BoxSprite.png|htiny]]
> ![[SRD-whismur-ShuffleToken.png|wsmall]]


*Whisper Pokemon*
*Their timid voice is barely audible, however, if it senses danger, they start crying loud enough to deafen anyone nearby. Their own noise scares them even more, so they cry harder until their ear covers shut.*

**DexID**:: 0293
**Name**:: Whismur
**Type**:: Normal
**Abilities**:: [[SRD-Soundproof|Soundproof]] ([[SRD-Rattled|Rattled]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'0" / 0.6m
**Weight**: 35.9lbs / 16.3kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Loudred]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Whismur.md"
flatten moves as T
where file.path = this.file.path
```
