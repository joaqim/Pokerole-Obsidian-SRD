---
Ability1: Water Compaction
Ability2: ''
BookSprite: SRD-palossand-BookSprite.png
BoxSprite: SRD-palossand-BoxSprite.png
DexCategory: Sand Castle Pokemon
DexDescription: The possessed people shaped this Pokemon into a castle, buried beneath
  the sand where it stands are the remains of all its victims. Some say these unmarked
  graves will give birth to a new Sandygast.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Sandygast]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Sand Veil
HomeSprite: SRD-palossand-HomeSprite.png
Image: palossand.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Harden|Harden]]'
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Tomb|Sand Tomb]]'
- - Beginner
  - '[[SRD-Mega Drain|Mega Drain]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Amateur
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Amateur
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Earth Power|Earth Power]]'
- - Ace
  - '[[SRD-Shore Up|Shore Up]]'
- - Ace
  - '[[SRD-Sandstorm|Sandstorm]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Rock Polish|Rock Polish]]'
- - Pro
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - Pro
  - '[[SRD-Earthquake|Earthquake]]'
Number: 770
ShuffleToken: SRD-palossand-ShuffleToken.png
Type1: Ghost
Type2: Ground
Weight:
  Kilograms: 250.0
  Pounds: 551.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-palossand-BookSprite.png|wsmall]]
> ![[SRD-palossand-HomeSprite.png]]
> ![[SRD-palossand-BoxSprite.png|htiny]]
> ![[SRD-palossand-ShuffleToken.png|wsmall]]


*Sand Castle Pokemon*
*The possessed people shaped this Pokemon into a castle, buried beneath the sand where it stands are the remains of all its victims. Some say these unmarked graves will give birth to a new Sandygast.*

**DexID**:: 0770
**Name**:: Palossand
**Type**:: Ghost / Ground
**Abilities**:: [[SRD-Water Compaction|Water Compaction]] ([[SRD-Sand Veil|Sand Veil]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'3" / 1.3m
**Weight**: 551.2lbs / 250.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Sandygast]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Palossand.md"
flatten moves as T
where file.path = this.file.path
```
