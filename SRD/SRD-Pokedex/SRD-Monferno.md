---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-monferno-BookSprite.png
BoxSprite: SRD-monferno-BoxSprite.png
DexCategory: Playful Pokemon
DexDescription: It bounces off walls and ceilings to launch aerial attacks. They live
  in packs in distant mountains. The size of their flame and the blue pattern on their
  faces determine their rank. They are small but very strong.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Chimchar]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Infernape]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Iron Fist
HomeSprite: SRD-monferno-HomeSprite.png
Image: monferno.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Taunt|Taunt]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Mach Punch|Mach Punch]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Flame Wheel|Flame Wheel]]'
- - Amateur
  - '[[SRD-Feint|Feint]]'
- - Amateur
  - '[[SRD-Torment|Torment]]'
- - Amateur
  - '[[SRD-Fire Spin|Fire Spin]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - Ace
  - '[[SRD-Acrobatics|Acrobatics]]'
- - Ace
  - '[[SRD-Slack Off|Slack Off]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Pro
  - '[[SRD-Fire Pledge|Fire Pledge]]'
Number: 391
ShuffleToken: SRD-monferno-ShuffleToken.png
Type1: Fire
Type2: Fighting
Weight:
  Kilograms: 22.0
  Pounds: 48.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-monferno-BookSprite.png|wsmall]]
> ![[SRD-monferno-HomeSprite.png]]
> ![[SRD-monferno-BoxSprite.png|htiny]]
> ![[SRD-monferno-ShuffleToken.png|wsmall]]


*Playful Pokemon*
*It bounces off walls and ceilings to launch aerial attacks. They live in packs in distant mountains. The size of their flame and the blue pattern on their faces determine their rank. They are small but very strong.*

**DexID**:: 0391
**Name**:: Monferno
**Type**:: Fire / Fighting
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Iron Fist|Iron Fist]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'0" / 0.9m
**Weight**: 48.5lbs / 22.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Chimchar]]  | Level  | Medium  |
| To        | [[SRD-Infernape]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Monferno.md"
flatten moves as T
where file.path = this.file.path
```
