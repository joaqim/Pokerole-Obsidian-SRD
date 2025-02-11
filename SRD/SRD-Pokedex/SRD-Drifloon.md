---
Ability1: Aftermath
Ability2: Unburden
BookSprite: SRD-drifloon-BookSprite.png
BoxSprite: SRD-drifloon-BoxSprite.png
DexCategory: Balloon Pokemon
DexDescription: "A Pokemon formed by the spirits of lost people and Pokemon. Children\
  \ who mistake it for a real balloon often end up missing. Because it floats aimlessly,\
  \ an old folktale calls it the \u201CSignpost for Wandering Spirits.\u201D"
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Drifblim]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Flare Boost
HomeSprite: SRD-drifloon-HomeSprite.png
Image: drifloon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Constrict|Constrict]]'
- - Starter
  - '[[SRD-Minimize|Minimize]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - Beginner
  - '[[SRD-Gust|Gust]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Amateur
  - '[[SRD-Payback|Payback]]'
- - Amateur
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Amateur
  - '[[SRD-Stockpile|Stockpile]]'
- - Amateur
  - '[[SRD-Hex|Hex]]'
- - Amateur
  - '[[SRD-Swallow|Swallow]]'
- - Amateur
  - '[[SRD-Spit Up|Spit Up]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Ace
  - '[[SRD-Amnesia|Amnesia]]'
- - Ace
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Disable|Disable]]'
- - Pro
  - '[[SRD-Weather Ball|Weather Ball]]'
- - Pro
  - '[[SRD-Sucker Punch|Sucker Punch]]'
Number: 425
ShuffleToken: SRD-drifloon-ShuffleToken.png
Type1: Ghost
Type2: Flying
Weight:
  Kilograms: 1.2
  Pounds: 2.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-drifloon-BookSprite.png|wsmall]]
> ![[SRD-drifloon-HomeSprite.png]]
> ![[SRD-drifloon-BoxSprite.png|htiny]]
> ![[SRD-drifloon-ShuffleToken.png|wsmall]]


*Balloon Pokemon*
*A Pokemon formed by the spirits of lost people and Pokemon. Children who mistake it for a real balloon often end up missing. Because it floats aimlessly, an old folktale calls it the “Signpost for Wandering Spirits.”*

**DexID**:: 0425
**Name**:: Drifloon
**Type**:: Ghost / Flying
**Abilities**:: [[SRD-Aftermath|Aftermath]] / [[SRD-Unburden|Unburden]] ([[SRD-Flare Boost|Flare Boost]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 2.6lbs / 1.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Drifblim]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Drifloon.md"
flatten moves as T
where file.path = this.file.path
```
