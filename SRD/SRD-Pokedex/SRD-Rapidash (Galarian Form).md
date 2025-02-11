---
Ability1: Run Away
Ability2: Pastel Veil
BookSprite: SRD-rapidash-galarian-form-BookSprite.png
BoxSprite: SRD-rapidash-galarian-form-BoxSprite.png
DexCategory: Unique Horn Pokemonn
DexDescription: Those with evil in their hearts will be disdained by this proud and
  beautiful Pokemon as it dashes on the air using its psychic power. It is said that
  only a true princess can mount a Galarian Rapidash.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Ponyta (Galarian Form)]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: Anticipation
HomeSprite: SRD-rapidash-galarian-form-HomeSprite.png
Image: rapidash-galarian-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fairy Wind|Fairy Wind]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Psycho Cut|Psycho Cut]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Stomp|Stomp]]'
- - Amateur
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Dazzling Gleam|Dazzling Gleam]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Megahorn|Megahorn]]'
- - Ace
  - '[[SRD-Healing Wish|Healing Wish]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-High Horsepower|High Horsepower]]'
- - Pro
  - '[[SRD-Magic Room|Magic Room]]'
- - Pro
  - '[[SRD-Bounce|Bounce]]'
Number: 78
ShuffleToken: SRD-rapidash-galarian-form-ShuffleToken.png
Type1: Psychic
Type2: Fairy
Weight:
  Kilograms: 80.0
  Pounds: 176.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-rapidash-galarian-form-BookSprite.png|wsmall]]
> ![[SRD-rapidash-galarian-form-HomeSprite.png]]
> ![[SRD-rapidash-galarian-form-BoxSprite.png|htiny]]
> ![[SRD-rapidash-galarian-form-ShuffleToken.png|wsmall]]


*Unique Horn Pokemonn*
*Those with evil in their hearts will be disdained by this proud and beautiful Pokemon as it dashes on the air using its psychic power. It is said that only a true princess can mount a Galarian Rapidash.*

**DexID**:: 0078G
**Name**:: Rapidash (Galarian Form)
**Type**:: Psychic / Fairy
**Abilities**:: [[SRD-Run Away|Run Away]] / [[SRD-Pastel Veil|Pastel Veil]] ([[SRD-Anticipation|Anticipation]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'6" / 1.7m
**Weight**: 176.4lbs / 80.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                        | Kind   | Speed   |
|:----------|:-------------------------------|:-------|:--------|
| From      | [[SRD-Ponyta (Galarian Form)]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Rapidash (Galarian Form).md"
flatten moves as T
where file.path = this.file.path
```
