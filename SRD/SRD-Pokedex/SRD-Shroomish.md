---
Ability1: Effect Spore
Ability2: Poison Heal
BookSprite: SRD-shroomish-BookSprite.png
BoxSprite: SRD-shroomish-BoxSprite.png
DexCategory: Mushroom Pokemon
DexDescription: They live in damp soil in forests, surrounded by moss. They suddenly
  release toxic spores that make plants dry up. These spores cause serious pain if
  inhaled. They grow taller with moisture and heat.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Breloom]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Quick Feet
HomeSprite: SRD-shroomish-HomeSprite.png
Image: shroomish.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tackle|Tackle]]'
- - Beginner
  - '[[SRD-Stun Spore|Stun Spore]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Poison Powder|Poison Powder]]'
- - Amateur
  - '[[SRD-Worry Seed|Worry Seed]]'
- - Amateur
  - '[[SRD-Growth|Growth]]'
- - Amateur
  - '[[SRD-Toxic|Toxic]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Ace
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Ace
  - '[[SRD-Spore|Spore]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Charm|Charm]]'
- - Pro
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
Number: 285
ShuffleToken: SRD-shroomish-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 4.5
  Pounds: 9.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-shroomish-BookSprite.png|wsmall]]
> ![[SRD-shroomish-HomeSprite.png]]
> ![[SRD-shroomish-BoxSprite.png|htiny]]
> ![[SRD-shroomish-ShuffleToken.png|wsmall]]


*Mushroom Pokemon*
*They live in damp soil in forests, surrounded by moss. They suddenly release toxic spores that make plants dry up. These spores cause serious pain if inhaled. They grow taller with moisture and heat.*

**DexID**:: 0285
**Name**:: Shroomish
**Type**:: Grass
**Abilities**:: [[SRD-Effect Spore|Effect Spore]] / [[SRD-Poison Heal|Poison Heal]] ([[SRD-Quick Feet|Quick Feet]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 9.9lbs / 4.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Breloom]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Shroomish.md"
flatten moves as T
where file.path = this.file.path
```
