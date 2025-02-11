---
Ability1: Pickup
Ability2: Technician
BookSprite: SRD-meowth-BookSprite.png
BoxSprite: SRD-meowth-BoxSprite.png
DexCategory: Scratch Cat Pokemon
DexDescription: They used to live in grasslands but have adapted really well to life
  in the city. Shiny things fascinate them and they keep a little treasure hidden.
  The coin on its head is its most prized possession.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Persian]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Unnerve
HomeSprite: SRD-meowth-HomeSprite.png
Image: meowth.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Fake Out|Fake Out]]'
- - Beginner
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Pay Day|Pay Day]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Captivate|Captivate]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Assurance|Assurance]]'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Feint|Feint]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Charm|Charm]]'
- - Pro
  - '[[SRD-Sing|Sing]]'
- - Pro
  - '[[SRD-Snatch|Snatch]]'
Number: 52
ShuffleToken: SRD-meowth-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 4.2
  Pounds: 9.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-meowth-BookSprite.png|wsmall]]
> ![[SRD-meowth-HomeSprite.png]]
> ![[SRD-meowth-BoxSprite.png|htiny]]
> ![[SRD-meowth-ShuffleToken.png|wsmall]]


*Scratch Cat Pokemon*
*They used to live in grasslands but have adapted really well to life in the city. Shiny things fascinate them and they keep a little treasure hidden. The coin on its head is its most prized possession.*

**DexID**:: 0052
**Name**:: Meowth
**Type**:: Normal
**Abilities**:: [[SRD-Pickup|Pickup]] / [[SRD-Technician|Technician]] ([[SRD-Unnerve|Unnerve]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 9.3lbs / 4.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Persian]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Meowth.md"
flatten moves as T
where file.path = this.file.path
```
