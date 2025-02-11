---
Ability1: Iron Barbs
Ability2: Lightning Rod
BookSprite: SRD-togedemaru-BookSprite.png
BoxSprite: SRD-togedemaru-BoxSprite.png
DexCategory: Roly-Poly Pokemon
DexDescription: On stormy days you can see groups of Togedemaru curled up into balls
  with their spikes out, waiting to be struck by lightning. These spikes also deter
  other Pokemon from attacking this cute creature.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Sturdy
HomeSprite: SRD-togedemaru-HomeSprite.png
Image: togedemaru.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Defense Curl|Defense Curl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Beginner
  - '[[SRD-Rollout|Rollout]]'
- - Beginner
  - '[[SRD-Charge|Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Nuzzle|Nuzzle]]'
- - Amateur
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Amateur
  - '[[SRD-Discharge|Discharge]]'
- - Amateur
  - '[[SRD-Zing Zap|Zing Zap]]'
- - Amateur
  - '[[SRD-Electric Terrain|Electric Terrain]]'
- - Amateur
  - '[[SRD-Wild Charge|Wild Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Pin Missile|Pin Missile]]'
- - Ace
  - '[[SRD-Spiky Shield|Spiky Shield]]'
- - Ace
  - '[[SRD-Fell Stinger|Fell Stinger]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Tickle|Tickle]]'
- - Pro
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Pro
  - '[[SRD-Present|Present]]'
Number: 777
ShuffleToken: SRD-togedemaru-ShuffleToken.png
Type1: Electric
Type2: Steel
Weight:
  Kilograms: 3.3
  Pounds: 7.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-togedemaru-BookSprite.png|wsmall]]
> ![[SRD-togedemaru-HomeSprite.png]]
> ![[SRD-togedemaru-BoxSprite.png|htiny]]
> ![[SRD-togedemaru-ShuffleToken.png|wsmall]]


*Roly-Poly Pokemon*
*On stormy days you can see groups of Togedemaru curled up into balls with their spikes out, waiting to be struck by lightning. These spikes also deter other Pokemon from attacking this cute creature.*

**DexID**:: 0777
**Name**:: Togedemaru
**Type**:: Electric / Steel
**Abilities**:: [[SRD-Iron Barbs|Iron Barbs]] / [[SRD-Lightning Rod|Lightning Rod]] ([[SRD-Sturdy|Sturdy]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 1'0" / 0.3m
**Weight**: 7.3lbs / 3.3kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Togedemaru.md"
flatten moves as T
where file.path = this.file.path
```
