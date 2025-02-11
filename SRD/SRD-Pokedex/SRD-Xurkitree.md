---
Ability1: Beast Boost
Ability2: ''
BookSprite: SRD-xurkitree-BookSprite.png
BoxSprite: SRD-xurkitree-BoxSprite.png
DexCategory: 'Aether Foundation Log #067'
DexDescription: My superiors are furious. A lot of money had to be used to cover the
  damages UB-03 dealt in the power plant. On the bright side, it seems a lot livelier
  now that it appears to have recharged.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 12.5
  Meters: 3.8
HiddenAbility: ''
HomeSprite: SRD-xurkitree-HomeSprite.png
Image: xurkitree.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Tail Glow|Tail Glow]]'
- - Master
  - '[[SRD-Spark|Spark]]'
- - Master
  - '[[SRD-Charge|Charge]]'
- - Master
  - '[[SRD-Wrap|Wrap]]'
- - Master
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Master
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Master
  - '[[SRD-Shock Wave|Shock Wave]]'
- - Master
  - '[[SRD-Ingrain|Ingrain]]'
- - Master
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Master
  - '[[SRD-Eerie Impulse|Eerie Impulse]]'
- - Master
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Master
  - '[[SRD-Thunderbolt|Thunderbolt]]'
- - Master
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Master
  - '[[SRD-Discharge|Discharge]]'
- - Master
  - '[[SRD-Electric Terrain|Electric Terrain]]'
- - Master
  - '[[SRD-Power Whip|Power Whip]]'
- - Master
  - '[[SRD-Ion Deluge|Ion Deluge]]'
- - Master
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - Master
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Master
  - '[[SRD-Brutal Swing|Brutal Swing]]'
- - Master
  - '[[SRD-Electroweb|Electroweb]]'
Number: 796
ShuffleToken: SRD-xurkitree-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 100.0
  Pounds: 220.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-xurkitree-BookSprite.png|wsmall]]
> ![[SRD-xurkitree-HomeSprite.png]]
> ![[SRD-xurkitree-BoxSprite.png|htiny]]
> ![[SRD-xurkitree-ShuffleToken.png|wsmall]]


*Aether Foundation Log #067*
*My superiors are furious. A lot of money had to be used to cover the damages UB-03 dealt in the power plant. On the bright side, it seems a lot livelier now that it appears to have recharged.*

**DexID**:: 0796
**Name**:: Xurkitree
**Type**:: Electric
**Abilities**:: [[SRD-Beast Boost|Beast Boost]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::9)/(MaxSpecial::9)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 12'5" / 3.8m
**Weight**: 220.5lbs / 100.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Xurkitree.md"
flatten moves as T
where file.path = this.file.path
```
