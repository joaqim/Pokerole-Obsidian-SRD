---
Ability1: Swift Swim
Ability2: Sniper
BookSprite: SRD-seadra-BookSprite.png
BoxSprite: SRD-seadra-BoxSprite.png
DexCategory: Dragon Pokemon
DexDescription: The poisonous barbs all over its body are highly valued as ingredients
  for making traditional medicine. It will show no mercy if anything approaches its
  nest. Its back fin has a numbing substance
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Horsea]]'
  Speed: Slow
- Evolves: To
  Item: Dragon Scale
  Kind: Trade
  Pokemon: '[[SRD-Kingdra]]'
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Damp
HomeSprite: SRD-seadra-HomeSprite.png
Image: seadra.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - Starter
  - '[[SRD-Smokescreen|Smokescreen]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - Beginner
  - '[[SRD-Bubble|Bubble]]'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Twister|Twister]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Ace
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Pro
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Pro
  - '[[SRD-Octazooka|Octazooka]]'
Number: 117
ShuffleToken: SRD-seadra-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 25.0
  Pounds: 55.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-seadra-BookSprite.png|wsmall]]
> ![[SRD-seadra-HomeSprite.png]]
> ![[SRD-seadra-BoxSprite.png|htiny]]
> ![[SRD-seadra-ShuffleToken.png|wsmall]]


*Dragon Pokemon*
*The poisonous barbs all over its body are highly valued as ingredients for making traditional medicine. It will show no mercy if anything approaches its nest. Its back fin has a numbing substance*

**DexID**:: 0117
**Name**:: Seadra
**Type**:: Water
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] / [[SRD-Sniper|Sniper]] ([[SRD-Damp|Damp]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'9" / 1.2m
**Weight**: 55.1lbs / 25.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   | Item         |
|:----------|:----------------|:-------|:--------|:-------------|
| From      | [[SRD-Horsea]]  | Level  | Slow    |              |
| To        | [[SRD-Kingdra]] | Trade  |         | Dragon Scale |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Seadra.md"
flatten moves as T
where file.path = this.file.path
```
