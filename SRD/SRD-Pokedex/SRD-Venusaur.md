---
Ability1: Overgrow
Ability2: ''
BookSprite: SRD-venusaur-BookSprite.png
BoxSprite: SRD-venusaur-BoxSprite.png
DexCategory: Seed Pokemon
DexDescription: "Venusaur's flower is said to take on vivid colors if it gets plenty\
  \ of sun light. The flower\u2019s aroma soothes the emotions of others.\nIf you\
  \ find one in the wild, it must be the protector of the area."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Ivysaur]]'
  Speed: Medium
- Evolves: To
  Item: Venusaurite
  Kind: Mega
  Pokemon: '[[SRD-Venusaur (Mega Form)]]'
GenderType: ''
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: Chlorophyll
HomeSprite: SRD-venusaur-HomeSprite.png
Image: venusaur.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Beginner
  - '[[SRD-Vine Whip|Vine Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Poison Powder|Poison Powder]]'
- - Amateur
  - '[[SRD-Sleep Powder|Sleep Powder]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[SRD-Growth|Growth]]'
- - Amateur
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Amateur
  - '[[SRD-Petal Dance|Petal Dance]]'
- - Amateur
  - '[[SRD-Worry Seed|Worry Seed]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Synthesis|Synthesis]]'
- - Ace
  - '[[SRD-Petal Blizzard|Petal Blizzard]]'
- - Ace
  - '[[SRD-Solar Beam|Solar Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
- - Pro
  - '[[SRD-Curse|Curse]]'
- - Pro
  - '[[SRD-Frenzy Plant|Frenzy Plant]]'
Number: 3
ShuffleToken: SRD-venusaur-ShuffleToken.png
Type1: Grass
Type2: Poison
Weight:
  Kilograms: 100.0
  Pounds: 220.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-venusaur-BookSprite.png|wsmall]]
> ![[SRD-venusaur-HomeSprite.png]]
> ![[SRD-venusaur-BoxSprite.png|htiny]]
> ![[SRD-venusaur-ShuffleToken.png|wsmall]]


*Seed Pokemon*
*Venusaur's flower is said to take on vivid colors if it gets plenty of sun light. The flower’s aroma soothes the emotions of others.
If you find one in the wild, it must be the protector of the area.*

**DexID**:: 0003
**Name**:: Venusaur
**Type**:: Grass / Poison
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Chlorophyll|Chlorophyll]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 6'6" / 2.0m
**Weight**: 220.5lbs / 100.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                      | Kind   | Speed   | Item        |
|:----------|:-----------------------------|:-------|:--------|:------------|
| From      | [[SRD-Ivysaur]]              | Level  | Medium  |             |
| To        | [[SRD-Venusaur (Mega Form)]] | Mega   |         | Venusaurite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Venusaur.md"
flatten moves as T
where file.path = this.file.path
```
