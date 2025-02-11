---
Ability1: Beast Boost
Ability2: ''
BookSprite: SRD-kartana-BookSprite.png
BoxSprite: SRD-kartana-BoxSprite.png
DexCategory: 'Aether Foundation Log #014'
DexDescription: Its paper-thin body and agility make it too dangerous to approach
  without serious risk of injury. Our team managed to immobilize it using a heat chamber,
  though I swear I feel its resentment to us.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: ''
HomeSprite: SRD-kartana-HomeSprite.png
Image: kartana.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Sacred Sword|Sacred Sword]]'
- - Master
  - '[[SRD-Defog|Defog]]'
- - Master
  - '[[SRD-Vacuum Wave|Vacuum Wave]]'
- - Master
  - '[[SRD-Air Cutter|Air Cutter]]'
- - Master
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Master
  - '[[SRD-Cut|Cut]]'
- - Master
  - '[[SRD-False Swipe|False Swipe]]'
- - Master
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Master
  - '[[SRD-Synthesis|Synthesis]]'
- - Master
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - Master
  - '[[SRD-Laser Focus|Laser Focus]]'
- - Master
  - '[[SRD-Night Slash|Night Slash]]'
- - Master
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Master
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - Master
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Master
  - '[[SRD-Detect|Detect]]'
- - Master
  - '[[SRD-Air Slash|Air Slash]]'
- - Master
  - '[[SRD-Psycho Cut|Psycho Cut]]'
- - Master
  - '[[SRD-Guillotine|Guillotine]]'
- - Master
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[SRD-Knock Off|Knock Off]]'
- - Master
  - '[[SRD-Tailwind|Tailwind]]'
Number: 798
ShuffleToken: SRD-kartana-ShuffleToken.png
Type1: Grass
Type2: Steel
Weight:
  Kilograms: 0.1
  Pounds: 0.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-kartana-BookSprite.png|wsmall]]
> ![[SRD-kartana-HomeSprite.png]]
> ![[SRD-kartana-BoxSprite.png|htiny]]
> ![[SRD-kartana-ShuffleToken.png|wsmall]]


*Aether Foundation Log #014*
*Its paper-thin body and agility make it too dangerous to approach without serious risk of injury. Our team managed to immobilize it using a heat chamber, though I swear I feel its resentment to us.*

**DexID**:: 0798
**Name**:: Kartana
**Type**:: Grass / Steel
**Abilities**:: [[SRD-Beast Boost|Beast Boost]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::9)/(MaxStrength::9)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::7)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::4)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 0.2lbs / 0.1kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Kartana.md"
flatten moves as T
where file.path = this.file.path
```
