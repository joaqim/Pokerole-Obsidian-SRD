---
Ability1: Water Absorb
Ability2: Shell Armor
BookSprite: SRD-lapras-BookSprite.png
BoxSprite: SRD-lapras-BoxSprite.png
DexCategory: Transport Pokemon
DexDescription: People have driven Lapras near the point of extinction. In the evenings,
  this Pokemon is said to sing as it seeks what few others of its kind still remain.
  Their gentle nature has made them easy to lure and catch.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 8.2
  Meters: 2.5
HiddenAbility: Hydration
HomeSprite: SRD-lapras-HomeSprite.png
Image: lapras.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Sing|Sing]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Mist|Mist]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Ice Beam|Ice Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Perish Song|Perish Song]]'
- - Ace
  - '[[SRD-Safeguard|Safeguard]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Pro
  - '[[SRD-Freeze Dry|Freeze Dry]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
Number: 131
ShuffleToken: SRD-lapras-ShuffleToken.png
Type1: Water
Type2: Ice
Weight:
  Kilograms: 220.0
  Pounds: 485.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-lapras-BookSprite.png|wsmall]]
> ![[SRD-lapras-HomeSprite.png]]
> ![[SRD-lapras-BoxSprite.png|htiny]]
> ![[SRD-lapras-ShuffleToken.png|wsmall]]


*Transport Pokemon*
*People have driven Lapras near the point of extinction. In the evenings, this Pokemon is said to sing as it seeks what few others of its kind still remain. Their gentle nature has made them easy to lure and catch.*

**DexID**:: 0131
**Name**:: Lapras
**Type**:: Water / Ice
**Abilities**:: [[SRD-Water Absorb|Water Absorb]] / [[SRD-Shell Armor|Shell Armor]] ([[SRD-Hydration|Hydration]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 8'2" / 2.5m
**Weight**: 485.0lbs / 220.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Lapras.md"
flatten moves as T
where file.path = this.file.path
```
