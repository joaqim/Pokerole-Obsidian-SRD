---
Ability1: Keen Eye
Ability2: Sturdy
BookSprite: SRD-skarmory-BookSprite.png
BoxSprite: SRD-skarmory-BoxSprite.png
DexCategory: Armor Bird Pokemon
DexDescription: Their wings are hollow and light. They nest inside bramble bushes,
  growing harder from scratches made by thorns. Their wings were used as swords and
  knives in old times. Beware of their sharp beak.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: Weak Armor
HomeSprite: SRD-skarmory-HomeSprite.png
Image: skarmory.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Peck|Peck]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Swift|Swift]]'
- - Beginner
  - '[[SRD-Metal Claw|Metal Claw]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Feint|Feint]]'
- - Amateur
  - '[[SRD-Air Cutter|Air Cutter]]'
- - Amateur
  - '[[SRD-Spikes|Spikes]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Steel Wing|Steel Wing]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Autotomize|Autotomize]]'
- - Ace
  - '[[SRD-Air Slash|Air Slash]]'
- - Ace
  - '[[SRD-Slash|Slash]]'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Pro
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Pro
  - '[[SRD-Pursuit|Pursuit]]'
Number: 227
ShuffleToken: SRD-skarmory-ShuffleToken.png
Type1: Steel
Type2: Flying
Weight:
  Kilograms: 50.5
  Pounds: 111.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-skarmory-BookSprite.png|wsmall]]
> ![[SRD-skarmory-HomeSprite.png]]
> ![[SRD-skarmory-BoxSprite.png|htiny]]
> ![[SRD-skarmory-ShuffleToken.png|wsmall]]


*Armor Bird Pokemon*
*Their wings are hollow and light. They nest inside bramble bushes, growing harder from scratches made by thorns. Their wings were used as swords and knives in old times. Beware of their sharp beak.*

**DexID**:: 0227
**Name**:: Skarmory
**Type**:: Steel / Flying
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Sturdy|Sturdy]] ([[SRD-Weak Armor|Weak Armor]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'6" / 1.7m
**Weight**: 111.3lbs / 50.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Skarmory.md"
flatten moves as T
where file.path = this.file.path
```
