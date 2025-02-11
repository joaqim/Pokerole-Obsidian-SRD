---
Ability1: Swift Swim
Ability2: Water Absorb
BookSprite: SRD-mantine-BookSprite.png
BoxSprite: SRD-mantine-BoxSprite.png
DexCategory: Kite Pokemon
DexDescription: Mantine swims under water and over the waves, gliding for 300 ft in
  the air. They are intelligent and docile, traveling elegantly in groups. Remoraids
  can be seen hanging from their fins from time to time.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Special
  Pokemon: '[[SRD-Mantyke]]'
  Special: Hit by Remoraid
GenderType: ''
Height:
  Feet: 6.9
  Meters: 2.1
HiddenAbility: Water Veil
HomeSprite: SRD-mantine-HomeSprite.png
Image: mantine.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bubble|Bubble]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Psybeam|Psybeam]]'
- - Beginner
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Beginner
  - '[[SRD-Supersonic|Supersonic]]'
- - Beginner
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Amateur
  - '[[SRD-Roost|Roost]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Wing Attack|Wing Attack]]'
- - Amateur
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Headbutt|Headbutt]]'
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
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - Pro
  - '[[SRD-Mud Sport|Mud Sport]]'
Number: 226
ShuffleToken: SRD-mantine-ShuffleToken.png
Type1: Water
Type2: Flying
Weight:
  Kilograms: 220.0
  Pounds: 485.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mantine-BookSprite.png|wsmall]]
> ![[SRD-mantine-HomeSprite.png]]
> ![[SRD-mantine-BoxSprite.png|htiny]]
> ![[SRD-mantine-ShuffleToken.png|wsmall]]


*Kite Pokemon*
*Mantine swims under water and over the waves, gliding for 300 ft in the air. They are intelligent and docile, traveling elegantly in groups. Remoraids can be seen hanging from their fins from time to time.*

**DexID**:: 0226
**Name**:: Mantine
**Type**:: Water / Flying
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] / [[SRD-Water Absorb|Water Absorb]] ([[SRD-Water Veil|Water Veil]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 6'9" / 2.1m
**Weight**: 485.0lbs / 220.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind    | Special         |
|:----------|:----------------|:--------|:----------------|
| From      | [[SRD-Mantyke]] | Special | Hit by Remoraid |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Mantine.md"
flatten moves as T
where file.path = this.file.path
```
