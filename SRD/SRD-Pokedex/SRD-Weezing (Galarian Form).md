---
Ability1: Levitate
Ability2: Neutralizing Gas
BookSprite: SRD-weezing-galarian-form-BookSprite.png
BoxSprite: SRD-weezing-galarian-form-BoxSprite.png
DexCategory: Poison Gas Pokemon
DexDescription: This Pokemon eats the contamination in the air, and instead of droppings,
  it expels clean air. Its Galar Form was first spotted long ago when factories polluted
  the City.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Koffing]]'
  Region: Galar
  Speed: Slow
GenderType: ''
Height:
  Feet: 9.8
  Meters: 3.0
HiddenAbility: Misty Surge
HomeSprite: SRD-weezing-galarian-form-HomeSprite.png
Image: weezing-galarian-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Poison Gas|Poison Gas]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fairy Wind|Fairy Wind]]'
- - Beginner
  - '[[SRD-Aromatic Mist|Aromatic Mist]]'
- - Beginner
  - '[[SRD-Clear Smog|Clear Smog]]'
- - Beginner
  - '[[SRD-Smog|Smog]]'
- - Beginner
  - '[[SRD-Smokescreen|Smokescreen]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Haze|Haze]]'
- - Amateur
  - '[[SRD-Defog|Defog]]'
- - Amateur
  - '[[SRD-Double Hit|Double Hit]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Sludge|Sludge]]'
- - Amateur
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Amateur
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Amateur
  - '[[SRD-Sludge Bomb|Sludge Bomb]]'
- - Amateur
  - '[[SRD-Toxic|Toxic]]'
- - Amateur
  - '[[SRD-Belch|Belch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - Ace
  - '[[SRD-Strange Steam|Strange Steam]]'
- - Ace
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - Ace
  - '[[SRD-Memento|Memento]]'
- - Ace
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Pro
  - '[[SRD-Stockpile|Stockpile]]'
- - Pro
  - '[[SRD-Swallow|Swallow]]'
Number: 110
ShuffleToken: SRD-weezing-galarian-form-ShuffleToken.png
Type1: Poison
Type2: Fairy
Weight:
  Kilograms: 16.0
  Pounds: 35.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-weezing-galarian-form-BookSprite.png|wsmall]]
> ![[SRD-weezing-galarian-form-HomeSprite.png]]
> ![[SRD-weezing-galarian-form-BoxSprite.png|htiny]]
> ![[SRD-weezing-galarian-form-ShuffleToken.png|wsmall]]


*Poison Gas Pokemon*
*This Pokemon eats the contamination in the air, and instead of droppings, it expels clean air. Its Galar Form was first spotted long ago when factories polluted the City.*

**DexID**:: 0110G
**Name**:: Weezing (Galarian Form)
**Type**:: Poison / Fairy
**Abilities**:: [[SRD-Levitate|Levitate]] / [[SRD-Neutralizing Gas|Neutralizing Gas]] ([[SRD-Misty Surge|Misty Surge]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 9'8" / 3.0m
**Weight**: 35.3lbs / 16.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   | Region   |
|:----------|:----------------|:-------|:--------|:---------|
| From      | [[SRD-Koffing]] | Level  | Slow    | Galar    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Weezing (Galarian Form).md"
flatten moves as T
where file.path = this.file.path
```
