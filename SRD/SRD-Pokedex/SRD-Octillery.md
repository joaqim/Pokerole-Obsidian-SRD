---
Ability1: Suction Cups
Ability2: Sniper
BookSprite: SRD-octillery-BookSprite.png
BoxSprite: SRD-octillery-BoxSprite.png
DexCategory: Jet Pokemon
DexDescription: Octillery sprays ink, traps its foes with its tentacles and then hits
  them with its rock-hard head. If the enemy is too strong, they escape. They can
  be found inside rocky holes deep in the sea floor.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Remoraid]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Moody
HomeSprite: SRD-octillery-HomeSprite.png
Image: octillery.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Starter
  - '[[SRD-Constrict|Constrict]]'
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Beginner
  - '[[SRD-Psybeam|Psybeam]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Amateur
  - '[[SRD-Octazooka|Octazooka]]'
- - Amateur
  - '[[SRD-Wring Out|Wring Out]]'
- - Amateur
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Amateur
  - '[[SRD-Ice Beam|Ice Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Gunk Shot|Gunk Shot]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Ace
  - '[[SRD-Soak|Soak]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Water Spout|Water Spout]]'
- - Pro
  - '[[SRD-Acid Spray|Acid Spray]]'
- - Pro
  - '[[SRD-Dive|Dive]]'
Number: 224
ShuffleToken: SRD-octillery-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 28.5
  Pounds: 62.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-octillery-BookSprite.png|wsmall]]
> ![[SRD-octillery-HomeSprite.png]]
> ![[SRD-octillery-BoxSprite.png|htiny]]
> ![[SRD-octillery-ShuffleToken.png|wsmall]]


*Jet Pokemon*
*Octillery sprays ink, traps its foes with its tentacles and then hits them with its rock-hard head. If the enemy is too strong, they escape. They can be found inside rocky holes deep in the sea floor.*

**DexID**:: 0224
**Name**:: Octillery
**Type**:: Water
**Abilities**:: [[SRD-Suction Cups|Suction Cups]] / [[SRD-Sniper|Sniper]] ([[SRD-Moody|Moody]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'0" / 0.9m
**Weight**: 62.8lbs / 28.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Remoraid]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Octillery.md"
flatten moves as T
where file.path = this.file.path
```
