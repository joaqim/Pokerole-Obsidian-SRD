---
Ability1: Intimidate
Ability2: ''
BookSprite: SRD-staraptor-BookSprite.png
BoxSprite: SRD-staraptor-BoxSprite.png
DexCategory: Predator Pokemon
DexDescription: Staraptor is a savage creature. They will never stop attacking even
  if they get injured,and will fight foes bigger than themselves. They are known to
  leave their flock to live on their own when they evolve.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Staravia]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Reckless
HomeSprite: SRD-staraptor-HomeSprite.png
Image: staraptor.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Wing Attack|Wing Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Double Team|Double Team]]'
- - Amateur
  - '[[SRD-Endeavor|Endeavor]]'
- - Amateur
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Amateur
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - Ace
  - '[[SRD-Agility|Agility]]'
- - Ace
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Ace
  - '[[SRD-Final Gambit|Final Gambit]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Twister|Twister]]'
- - Pro
  - '[[SRD-Roost|Roost]]'
- - Pro
  - '[[SRD-Steel Wing|Steel Wing]]'
Number: 398
ShuffleToken: SRD-staraptor-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 24.9
  Pounds: 54.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-staraptor-BookSprite.png|wsmall]]
> ![[SRD-staraptor-HomeSprite.png]]
> ![[SRD-staraptor-BoxSprite.png|htiny]]
> ![[SRD-staraptor-ShuffleToken.png|wsmall]]


*Predator Pokemon*
*Staraptor is a savage creature. They will never stop attacking even if they get injured,and will fight foes bigger than themselves. They are known to leave their flock to live on their own when they evolve.*

**DexID**:: 0398
**Name**:: Staraptor
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Intimidate|Intimidate]] ([[SRD-Reckless|Reckless]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'9" / 1.2m
**Weight**: 54.9lbs / 24.9kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Staravia]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Staraptor.md"
flatten moves as T
where file.path = this.file.path
```
