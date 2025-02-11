---
Ability1: Misty Surge
Ability2: ''
BookSprite: SRD-tapu-fini-BookSprite.png
BoxSprite: SRD-tapu-fini-BoxSprite.png
DexCategory: No Data
DexDescription: The people on Poni island are proud of the clean water on their land,
  for that they thank their guardian spirit who is said to be the ocean itself.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Telepathy
HomeSprite: SRD-tapu-fini-HomeSprite.png
Image: tapu-fini.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - Master
  - '[[SRD-Moonblast|Moonblast]]'
- - Master
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Master
  - '[[SRD-Mean Look|Mean Look]]'
- - Master
  - '[[SRD-Haze|Haze]]'
- - Master
  - '[[SRD-Mist|Mist]]'
- - Master
  - '[[SRD-Withdraw|Withdraw]]'
- - Master
  - '[[SRD-Water Gun|Water Gun]]'
- - Master
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Master
  - '[[SRD-Whirlpool|Whirlpool]]'
- - Master
  - '[[SRD-Soak|Soak]]'
- - Master
  - '[[SRD-Refresh|Refresh]]'
- - Master
  - '[[SRD-Brine|Brine]]'
- - Master
  - '[[SRD-Defog|Defog]]'
- - Master
  - '[[SRD-Nature''s Madness|Nature''s Madness]]'
- - Master
  - '[[SRD-Muddy Water|Muddy Water]]'
- - Master
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Master
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Master
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Master
  - '[[SRD-Wonder Room|Wonder Room]]'
- - Master
  - '[[SRD-Knock Off|Knock Off]]'
Number: 788
ShuffleToken: SRD-tapu-fini-ShuffleToken.png
Type1: Water
Type2: Fairy
Weight:
  Kilograms: 21.2
  Pounds: 46.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tapu-fini-BookSprite.png|wsmall]]
> ![[SRD-tapu-fini-HomeSprite.png]]
> ![[SRD-tapu-fini-BoxSprite.png|htiny]]
> ![[SRD-tapu-fini-ShuffleToken.png|wsmall]]


*No Data*
*The people on Poni island are proud of the clean water on their land, for that they thank their guardian spirit who is said to be the ocean itself.*

**DexID**:: 0788
**Name**:: Tapu Fini
**Type**:: Water / Fairy
**Abilities**:: [[SRD-Misty Surge|Misty Surge]] ([[SRD-Telepathy|Telepathy]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::7)/(MaxInsight::7)     |

**Height**: 4'3" / 1.3m
**Weight**: 46.7lbs / 21.2kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Tapu Fini.md"
flatten moves as T
where file.path = this.file.path
```
