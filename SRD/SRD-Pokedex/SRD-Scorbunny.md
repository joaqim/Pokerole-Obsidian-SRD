---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-scorbunny-BookSprite.png
BoxSprite: SRD-scorbunny-BoxSprite.png
DexCategory: Rabbit Pokemon
DexDescription: Scorbunny is small and energetic, they love to run in large fields
  from one side to another for hours. There are heat pads on its feet and nose, as
  it runs or battles they can get burning hot.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Raboot]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Libero
HomeSprite: SRD-scorbunny-HomeSprite.png
Image: scorbunny.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Double Kick|Double Kick]]'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Counter|Counter]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bounce|Bounce]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fire Pledge|Fire Pledge]]'
- - Pro
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Pro
  - '[[SRD-Super Fang|Super Fang]]'
Number: 813
ShuffleToken: SRD-scorbunny-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 4.5
  Pounds: 9.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-scorbunny-BookSprite.png|wsmall]]
> ![[SRD-scorbunny-HomeSprite.png]]
> ![[SRD-scorbunny-BoxSprite.png|htiny]]
> ![[SRD-scorbunny-ShuffleToken.png|wsmall]]


*Rabbit Pokemon*
*Scorbunny is small and energetic, they love to run in large fields from one side to another for hours. There are heat pads on its feet and nose, as it runs or battles they can get burning hot.*

**DexID**:: 0813
**Name**:: Scorbunny
**Type**:: Fire
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Libero|Libero]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 9.9lbs / 4.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| To        | [[SRD-Raboot]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Scorbunny.md"
flatten moves as T
where file.path = this.file.path
```
