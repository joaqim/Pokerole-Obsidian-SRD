---
Ability1: Oblivious
Ability2: Snow Cloak
BookSprite: SRD-mamoswine-BookSprite.png
BoxSprite: SRD-mamoswine-BoxSprite.png
DexCategory: Twin Tusk Pokemon
DexDescription: It was everywhere during the ice age but its population declined afterwards.
  This Pokemon uses strong tusks to remove the soil and snow and dig up roots and
  plants to eat. It has a bad temper.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Piloswine]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 8.2
  Meters: 2.5
HiddenAbility: Thick Fat
HomeSprite: SRD-mamoswine-HomeSprite.png
Image: mamoswine.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Starter
  - '[[SRD-Mud Sport|Mud Sport]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Powder Snow|Powder Snow]]'
- - Beginner
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Beginner
  - '[[SRD-Scary Face|Scary Face]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Endure|Endure]]'
- - Amateur
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - Amateur
  - '[[SRD-Hail|Hail]]'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Double Hit|Double Hit]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Mist|Mist]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fissure|Fissure]]'
- - Pro
  - '[[SRD-Icicle Crash|Icicle Crash]]'
- - Pro
  - '[[SRD-Avalanche|Avalanche]]'
Number: 473
ShuffleToken: SRD-mamoswine-ShuffleToken.png
Type1: Ice
Type2: Ground
Weight:
  Kilograms: 291.0
  Pounds: 641.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mamoswine-BookSprite.png|wsmall]]
> ![[SRD-mamoswine-HomeSprite.png]]
> ![[SRD-mamoswine-BoxSprite.png|htiny]]
> ![[SRD-mamoswine-ShuffleToken.png|wsmall]]


*Twin Tusk Pokemon*
*It was everywhere during the ice age but its population declined afterwards. This Pokemon uses strong tusks to remove the soil and snow and dig up roots and plants to eat. It has a bad temper.*

**DexID**:: 0473
**Name**:: Mamoswine
**Type**:: Ice / Ground
**Abilities**:: [[SRD-Oblivious|Oblivious]] / [[SRD-Snow Cloak|Snow Cloak]] ([[SRD-Thick Fat|Thick Fat]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 8'2" / 2.5m
**Weight**: 641.5lbs / 291.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Piloswine]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Mamoswine.md"
flatten moves as T
where file.path = this.file.path
```
