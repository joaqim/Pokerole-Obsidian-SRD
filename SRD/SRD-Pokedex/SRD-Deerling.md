---
Ability1: Chlorophyll
Ability2: Sap Sipper
BookSprite: SRD-deerling-BookSprite.png
BoxSprite: SRD-deerling-BoxSprite.png
DexCategory: Season Pokemon
DexDescription: They are born at the beginning of the spring. Their coloring changes
  according to the season and can be affected by temperature as well. It usually stays
  hidden in tall grass while its mother is away.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Sawsbuck]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Serene Grace
HomeSprite: SRD-deerling-HomeSprite.png
Image: deerling.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Camouflage|Camouflage]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Double Kick|Double Kick]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Jump Kick|Jump Kick]]'
- - Amateur
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Amateur
  - '[[SRD-Energy Ball|Energy Ball]]'
- - Amateur
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Nature Power|Nature Power]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Solar Beam|Solar Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Agility|Agility]]'
- - Pro
  - '[[SRD-Bounce|Bounce]]'
- - Pro
  - '[[SRD-Grass Whistle|Grass Whistle]]'
Number: 585
ShuffleToken: SRD-deerling-ShuffleToken.png
Type1: Normal
Type2: Grass
Weight:
  Kilograms: 19.5
  Pounds: 43.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-deerling-BookSprite.png|wsmall]]
> ![[SRD-deerling-HomeSprite.png]]
> ![[SRD-deerling-BoxSprite.png|htiny]]
> ![[SRD-deerling-ShuffleToken.png|wsmall]]


*Season Pokemon*
*They are born at the beginning of the spring. Their coloring changes according to the season and can be affected by temperature as well. It usually stays hidden in tall grass while its mother is away.*

**DexID**:: 0585
**Name**:: Deerling
**Type**:: Normal / Grass
**Abilities**:: [[SRD-Chlorophyll|Chlorophyll]] / [[SRD-Sap Sipper|Sap Sipper]] ([[SRD-Serene Grace|Serene Grace]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 43.0lbs / 19.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Sawsbuck]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Deerling.md"
flatten moves as T
where file.path = this.file.path
```
