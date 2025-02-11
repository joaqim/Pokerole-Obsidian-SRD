---
Ability1: Damp
Ability2: Cloud Nine
BookSprite: SRD-golduck-BookSprite.png
BoxSprite: SRD-golduck-BoxSprite.png
DexCategory: Duck Pokemon
DexDescription: A Golduck is an adept swimmer and can be found near most bodies of
  water. Its forehead shimmers with light when using its psychic abilities. There
  are records of wild Golducks that rescued people in the water.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Psyduck]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: Swift Swim
HomeSprite: SRD-golduck-HomeSprite.png
Image: golduck.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Water Sport|Water Sport]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Disable|Disable]]'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Soak|Soak]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psych Up|Psych Up]]'
- - Ace
  - '[[SRD-Me First|Me First]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Wonder Room|Wonder Room]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Tri Attack|Tri Attack]]'
- - Pro
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Pro
  - '[[SRD-Future Sight|Future Sight]]'
Number: 55
ShuffleToken: SRD-golduck-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 76.6
  Pounds: 168.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-golduck-BookSprite.png|wsmall]]
> ![[SRD-golduck-HomeSprite.png]]
> ![[SRD-golduck-BoxSprite.png|htiny]]
> ![[SRD-golduck-ShuffleToken.png|wsmall]]


*Duck Pokemon*
*A Golduck is an adept swimmer and can be found near most bodies of water. Its forehead shimmers with light when using its psychic abilities. There are records of wild Golducks that rescued people in the water.*

**DexID**:: 0055
**Name**:: Golduck
**Type**:: Water
**Abilities**:: [[SRD-Damp|Damp]] / [[SRD-Cloud Nine|Cloud Nine]] ([[SRD-Swift Swim|Swift Swim]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'6" / 1.7m
**Weight**: 168.9lbs / 76.6kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Psyduck]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Golduck.md"
flatten moves as T
where file.path = this.file.path
```
