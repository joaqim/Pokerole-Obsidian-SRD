---
Ability1: Swift Swim
Ability2: Shell Armor
BookSprite: SRD-omanyte-BookSprite.png
BoxSprite: SRD-omanyte-BoxSprite.png
DexCategory: Spiral Pokemon
DexDescription: One of the ancient and extinct Pokemon that have been revived from
  fossils by science. If attacked, it withdraws into its hard shell. It is not found
  in the wild anymore, but fossils can be found in the sea.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Omastar]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Weak Armor
HomeSprite: SRD-omanyte-HomeSprite.png
Image: omanyte.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Constrict|Constrict]]'
- - Starter
  - '[[SRD-Withdraw|Withdraw]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Rollout|Rollout]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Leer|Leer]]'
- - Amateur
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Tickle|Tickle]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Ace
  - '[[SRD-Shell Smash|Shell Smash]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Pro
  - '[[SRD-Spikes|Spikes]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
Number: 138
ShuffleToken: SRD-omanyte-ShuffleToken.png
Type1: Rock
Type2: Water
Weight:
  Kilograms: 7.5
  Pounds: 16.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-omanyte-BookSprite.png|wsmall]]
> ![[SRD-omanyte-HomeSprite.png]]
> ![[SRD-omanyte-BoxSprite.png|htiny]]
> ![[SRD-omanyte-ShuffleToken.png|wsmall]]


*Spiral Pokemon*
*One of the ancient and extinct Pokemon that have been revived from fossils by science. If attacked, it withdraws into its hard shell. It is not found in the wild anymore, but fossils can be found in the sea.*

**DexID**:: 0138
**Name**:: Omanyte
**Type**:: Rock / Water
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] / [[SRD-Shell Armor|Shell Armor]] ([[SRD-Weak Armor|Weak Armor]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 16.5lbs / 7.5kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Omastar]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Omanyte.md"
flatten moves as T
where file.path = this.file.path
```
