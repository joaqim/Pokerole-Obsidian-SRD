---
Ability1: Swift Swim
Ability2: Water Absorb
BookSprite: SRD-mantyke-BookSprite.png
BoxSprite: SRD-mantyke-BoxSprite.png
DexCategory: Kite Pokemon
DexDescription: "When it swims close the ocean\u2019s surface people aboard ships\
  \ are able to observe the pattern on its back as it is different in every region.\
  \ Mantyke is an intelligent and friendly Pokemon that rarely attacks others."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Special
  Pokemon: '[[SRD-Mantine]]'
  Special: Hit by Remoraid
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Water Veil
HomeSprite: SRD-mantyke-HomeSprite.png
Image: mantyke.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Bubble|Bubble]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Supersonic|Supersonic]]'
- - Beginner
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Beginner
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Wing Attack|Wing Attack]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Air Slash|Air Slash]]'
- - Ace
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Ace
  - '[[SRD-Bounce|Bounce]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Twister|Twister]]'
- - Pro
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Pro
  - '[[SRD-Tailwind|Tailwind]]'
Number: 458
ShuffleToken: SRD-mantyke-ShuffleToken.png
Type1: Water
Type2: Flying
Weight:
  Kilograms: 65.0
  Pounds: 143.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mantyke-BookSprite.png|wsmall]]
> ![[SRD-mantyke-HomeSprite.png]]
> ![[SRD-mantyke-BoxSprite.png|htiny]]
> ![[SRD-mantyke-ShuffleToken.png|wsmall]]


*Kite Pokemon*
*When it swims close the ocean’s surface people aboard ships are able to observe the pattern on its back as it is different in every region. Mantyke is an intelligent and friendly Pokemon that rarely attacks others.*

**DexID**:: 0458
**Name**:: Mantyke
**Type**:: Water / Flying
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] / [[SRD-Water Absorb|Water Absorb]] ([[SRD-Water Veil|Water Veil]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'3" / 1.0m
**Weight**: 143.3lbs / 65.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind    | Special         |
|:----------|:----------------|:--------|:----------------|
| To        | [[SRD-Mantine]] | Special | Hit by Remoraid |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Mantyke.md"
flatten moves as T
where file.path = this.file.path
```
