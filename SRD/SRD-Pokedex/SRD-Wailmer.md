---
Ability1: Water Veil
Ability2: Oblivious
BookSprite: SRD-wailmer-BookSprite.png
BoxSprite: SRD-wailmer-BoxSprite.png
DexCategory: Ball Whale Pokemon
DexDescription: Wailmer has a playful nature. They can store water inside their body
  to inflate like a ball and bounce, then startle people by snorting the water from
  their nostrils. This Pokemon needs lots of food everyday.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Wailord]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: Pressure
HomeSprite: SRD-wailmer-HomeSprite.png
Image: wailmer.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Splash|Splash]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Rollout|Rollout]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Whirlpool|Whirlpool]]'
- - Amateur
  - '[[SRD-Astonish|Astonish]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Mist|Mist]]'
- - Amateur
  - '[[SRD-Dive|Dive]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Water Spout|Water Spout]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rest|Rest]]'
- - Ace
  - '[[SRD-Bounce|Bounce]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Soak|Soak]]'
- - Pro
  - '[[SRD-Clear Smog|Clear Smog]]'
- - Pro
  - '[[SRD-Defense Curl|Defense Curl]]'
Number: 320
ShuffleToken: SRD-wailmer-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 130.0
  Pounds: 286.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-wailmer-BookSprite.png|wsmall]]
> ![[SRD-wailmer-HomeSprite.png]]
> ![[SRD-wailmer-BoxSprite.png|htiny]]
> ![[SRD-wailmer-ShuffleToken.png|wsmall]]


*Ball Whale Pokemon*
*Wailmer has a playful nature. They can store water inside their body to inflate like a ball and bounce, then startle people by snorting the water from their nostrils. This Pokemon needs lots of food everyday.*

**DexID**:: 0320
**Name**:: Wailmer
**Type**:: Water
**Abilities**:: [[SRD-Water Veil|Water Veil]] / [[SRD-Oblivious|Oblivious]] ([[SRD-Pressure|Pressure]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 6'6" / 2.0m
**Weight**: 286.6lbs / 130.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Wailord]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Wailmer.md"
flatten moves as T
where file.path = this.file.path
```
