---
Ability1: Iron Barbs
Ability2: ''
BookSprite: SRD-ferrothorn-BookSprite.png
BoxSprite: SRD-ferrothorn-BoxSprite.png
DexCategory: Thorn Pod Pokemon
DexDescription: It attaches itself to cave ceilings by swinging around its spiky feelers.
  It shoots spikes at targets passing beneath. It is incredibly resilient and stubborn,
  it will whip you if you try to take its spot in the cave walls..
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Ferroseed]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Anticipation
HomeSprite: SRD-ferrothorn-HomeSprite.png
Image: ferrothorn.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Harden|Harden]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Curse|Curse]]'
- - Beginner
  - '[[SRD-Rollout|Rollout]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rock Climb|Rock Climb]]'
- - Amateur
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Amateur
  - '[[SRD-Pin Missile|Pin Missile]]'
- - Amateur
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Mirror Shot|Mirror Shot]]'
- - Amateur
  - '[[SRD-Ingrain|Ingrain]]'
- - Amateur
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Amateur
  - '[[SRD-Power Whip|Power Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Iron Head|Iron Head]]'
- - Ace
  - '[[SRD-Payback|Payback]]'
- - Ace
  - '[[SRD-Flash Cannon|Flash Cannon]]'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
Number: 598
ShuffleToken: SRD-ferrothorn-ShuffleToken.png
Type1: Grass
Type2: Steel
Weight:
  Kilograms: 110.0
  Pounds: 242.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-ferrothorn-BookSprite.png|wsmall]]
> ![[SRD-ferrothorn-HomeSprite.png]]
> ![[SRD-ferrothorn-BoxSprite.png|htiny]]
> ![[SRD-ferrothorn-ShuffleToken.png|wsmall]]


*Thorn Pod Pokemon*
*It attaches itself to cave ceilings by swinging around its spiky feelers. It shoots spikes at targets passing beneath. It is incredibly resilient and stubborn, it will whip you if you try to take its spot in the cave walls..*

**DexID**:: 0598
**Name**:: Ferrothorn
**Type**:: Grass / Steel
**Abilities**:: [[SRD-Iron Barbs|Iron Barbs]] ([[SRD-Anticipation|Anticipation]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'3" / 1.0m
**Weight**: 242.5lbs / 110.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Ferroseed]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Ferrothorn.md"
flatten moves as T
where file.path = this.file.path
```
