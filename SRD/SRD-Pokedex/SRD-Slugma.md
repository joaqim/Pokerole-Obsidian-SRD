---
Ability1: Magma Armor
Ability2: Flame Body
BookSprite: SRD-slugma-BookSprite.png
BoxSprite: SRD-slugma-BoxSprite.png
DexCategory: Lava Pokemon
DexDescription: They are extremely common in volcanic areas where they group together.
  They are made of molten magma instead of blood and flesh. Slugmas replenish parts
  of their body by absorbing molted rocks.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Magcargo]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Weak Armor
HomeSprite: SRD-slugma-HomeSprite.png
Image: slugma.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Smog|Smog]]'
- - Starter
  - '[[SRD-Yawn|Yawn]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Rock Throw|Rock Throw]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Harden|Harden]]'
- - Amateur
  - '[[SRD-Incinerate|Incinerate]]'
- - Amateur
  - '[[SRD-Clear Smog|Clear Smog]]'
- - Amateur
  - '[[SRD-Recover|Recover]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Lava Plume|Lava Plume]]'
- - Ace
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Ace
  - '[[SRD-Earth Power|Earth Power]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Pro
  - '[[SRD-Smokescreen|Smokescreen]]'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
Number: 218
ShuffleToken: SRD-slugma-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 35.0
  Pounds: 77.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-slugma-BookSprite.png|wsmall]]
> ![[SRD-slugma-HomeSprite.png]]
> ![[SRD-slugma-BoxSprite.png|htiny]]
> ![[SRD-slugma-ShuffleToken.png|wsmall]]


*Lava Pokemon*
*They are extremely common in volcanic areas where they group together. They are made of molten magma instead of blood and flesh. Slugmas replenish parts of their body by absorbing molted rocks.*

**DexID**:: 0218
**Name**:: Slugma
**Type**:: Fire
**Abilities**:: [[SRD-Magma Armor|Magma Armor]] / [[SRD-Flame Body|Flame Body]] ([[SRD-Weak Armor|Weak Armor]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'3" / 0.7m
**Weight**: 77.2lbs / 35.0kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Magcargo]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Slugma.md"
flatten moves as T
where file.path = this.file.path
```
