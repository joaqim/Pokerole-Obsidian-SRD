---
Ability1: Sturdy
Ability2: Inner Focus
BookSprite: SRD-sawk-BookSprite.png
BoxSprite: SRD-sawk-BoxSprite.png
DexCategory: Karate Pokemon
DexDescription: This Pokemon is entirely dedicated to becoming stronger. Many have
  secluded in the mountains to train all day. Wild ones make their clothes out of
  plants and vines they find. Sawk and Throh train together.
EventAbilities: ''
Evolutions: []
GenderType: M
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Mold Breaker
HomeSprite: SRD-sawk-HomeSprite.png
Image: sawk.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Rock Smash|Rock Smash]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bide|Bide]]'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Double Kick|Double Kick]]'
- - Amateur
  - '[[SRD-Low Sweep|Low Sweep]]'
- - Amateur
  - '[[SRD-Counter|Counter]]'
- - Amateur
  - '[[SRD-Karate Chop|Karate Chop]]'
- - Amateur
  - '[[SRD-Brick Break|Brick Break]]'
- - Amateur
  - '[[SRD-Bulk Up|Bulk Up]]'
- - Amateur
  - '[[SRD-Retaliate|Retaliate]]'
- - Amateur
  - '[[SRD-Endure|Endure]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dual Chop|Dual Chop]]'
- - Pro
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Pro
  - '[[SRD-Block|Block]]'
Number: 539
ShuffleToken: SRD-sawk-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 51.0
  Pounds: 112.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sawk-BookSprite.png|wsmall]]
> ![[SRD-sawk-HomeSprite.png]]
> ![[SRD-sawk-BoxSprite.png|htiny]]
> ![[SRD-sawk-ShuffleToken.png|wsmall]]


*Karate Pokemon*
*This Pokemon is entirely dedicated to becoming stronger. Many have secluded in the mountains to train all day. Wild ones make their clothes out of plants and vines they find. Sawk and Throh train together.*

**DexID**:: 0539
**Name**:: Sawk
**Type**:: Fighting
**Abilities**:: [[SRD-Sturdy|Sturdy]] / [[SRD-Inner Focus|Inner Focus]] ([[SRD-Mold Breaker|Mold Breaker]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'6" / 1.4m
**Weight**: 112.4lbs / 51.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Sawk.md"
flatten moves as T
where file.path = this.file.path
```
