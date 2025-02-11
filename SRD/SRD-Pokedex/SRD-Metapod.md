---
Ability1: Shed Skin
Ability2: ''
BookSprite: SRD-metapod-BookSprite.png
BoxSprite: SRD-metapod-BoxSprite.png
DexCategory: Cocoon Pokemon
DexDescription: Its shell can be as hard as an iron slab. A Metapod does not move
  very much because it is preparing its soft innards for evolution inside the shell.
  It is known as one of the fastest evolving Pokemon in the world.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Caterpie]]'
  Speed: Fast
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Butterfree]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: ''
HomeSprite: SRD-metapod-HomeSprite.png
Image: metapod.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Electroweb|Electroweb]]'
Number: 11
ShuffleToken: SRD-metapod-ShuffleToken.png
Type1: Bug
Type2: ''
Weight:
  Kilograms: 9.9
  Pounds: 21.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-metapod-BookSprite.png|wsmall]]
> ![[SRD-metapod-HomeSprite.png]]
> ![[SRD-metapod-BoxSprite.png|htiny]]
> ![[SRD-metapod-ShuffleToken.png|wsmall]]


*Cocoon Pokemon*
*Its shell can be as hard as an iron slab. A Metapod does not move very much because it is preparing its soft innards for evolution inside the shell. It is known as one of the fastest evolving Pokemon in the world.*

**DexID**:: 0011
**Name**:: Metapod
**Type**:: Bug
**Abilities**:: [[SRD-Shed Skin|Shed Skin]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'3" / 0.7m
**Weight**: 21.8lbs / 9.9kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| From      | [[SRD-Caterpie]]   | Level  | Fast    |
| To        | [[SRD-Butterfree]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Metapod.md"
flatten moves as T
where file.path = this.file.path
```
