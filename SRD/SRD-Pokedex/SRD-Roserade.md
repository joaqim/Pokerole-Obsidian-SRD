---
Ability1: Natural Cure
Ability2: Poison Point
BookSprite: SRD-roserade-BookSprite.png
BoxSprite: SRD-roserade-BoxSprite.png
DexCategory: Bouquet Pokemon
DexDescription: "Luring prey with a sweet scent, it uses the poison on its thorn-filled\
  \ arm-whips to poison, bind and finish off the prey. It has a dangerous appeal mixed\
  \ with a graceful personality. It\u2019s very rare in the wild."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Shiny Stone
  Kind: Stone
  Pokemon: '[[SRD-Roselia]]'
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Technician
HomeSprite: SRD-roserade-HomeSprite.png
Image: roserade.png
Legendary: 'No'
Moves:
- - Beginner
  - '[[SRD-Poison Sting|Poison Sting]]'
- - Beginner
  - '[[SRD-Grassy Terrain|Grassy Terrain]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Weather Ball|Weather Ball]]'
- - Amateur
  - '[[SRD-Venom Drench|Venom Drench]]'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Pro
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - Pro
  - '[[SRD-Pin Missile|Pin Missile]]'
Number: 407
ShuffleToken: SRD-roserade-ShuffleToken.png
Type1: Grass
Type2: Poison
Weight:
  Kilograms: 14.5
  Pounds: 32.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-roserade-BookSprite.png|wsmall]]
> ![[SRD-roserade-HomeSprite.png]]
> ![[SRD-roserade-BoxSprite.png|htiny]]
> ![[SRD-roserade-ShuffleToken.png|wsmall]]


*Bouquet Pokemon*
*Luring prey with a sweet scent, it uses the poison on its thorn-filled arm-whips to poison, bind and finish off the prey. It has a dangerous appeal mixed with a graceful personality. It’s very rare in the wild.*

**DexID**:: 0407
**Name**:: Roserade
**Type**:: Grass / Poison
**Abilities**:: [[SRD-Natural Cure|Natural Cure]] / [[SRD-Poison Point|Poison Point]] ([[SRD-Technician|Technician]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'0" / 0.9m
**Weight**: 32.0lbs / 14.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Item        |
|:----------|:----------------|:-------|:------------|
| From      | [[SRD-Roselia]] | Stone  | Shiny Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Roserade.md"
flatten moves as T
where file.path = this.file.path
```
