---
Ability1: Compound Eyes
Ability2: ''
BookSprite: SRD-nincada-BookSprite.png
BoxSprite: SRD-nincada-BoxSprite.png
DexCategory: Trainee Pokemon
DexDescription: They live underground for decades, absorbing nutrients from roots
  and waiting for evolution. Nincadas are nearly blind and cannot stand bright lights.
  They only come out to make a cocoon to evolve.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Ninjask]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Shedinja]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Run Away
HomeSprite: SRD-nincada-HomeSprite.png
Image: nincada.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Harden|Harden]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Leech Life|Leech Life]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Mind Reader|Mind Reader]]'
- - Amateur
  - '[[SRD-False Swipe|False Swipe]]'
- - Amateur
  - '[[SRD-Bide|Bide]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Ace
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Ace
  - '[[SRD-Dig|Dig]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Silver Wind|Silver Wind]]'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
Number: 290
ShuffleToken: SRD-nincada-ShuffleToken.png
Type1: Bug
Type2: Ground
Weight:
  Kilograms: 5.5
  Pounds: 12.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-nincada-BookSprite.png|wsmall]]
> ![[SRD-nincada-HomeSprite.png]]
> ![[SRD-nincada-BoxSprite.png|htiny]]
> ![[SRD-nincada-ShuffleToken.png|wsmall]]


*Trainee Pokemon*
*They live underground for decades, absorbing nutrients from roots and waiting for evolution. Nincadas are nearly blind and cannot stand bright lights. They only come out to make a cocoon to evolve.*

**DexID**:: 0290
**Name**:: Nincada
**Type**:: Bug / Ground
**Abilities**:: [[SRD-Compound Eyes|Compound Eyes]] ([[SRD-Run Away|Run Away]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'6" / 0.5m
**Weight**: 12.1lbs / 5.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Ninjask]]  | Level  | Medium  |
| To        | [[SRD-Shedinja]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Nincada.md"
flatten moves as T
where file.path = this.file.path
```
