---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-flygon-BookSprite.png
BoxSprite: SRD-flygon-BoxSprite.png
DexCategory: Mystic Pokemon
DexDescription: "Known as the \u201CElemental Spirit of the Desert\u201D. Their wings\
  \ create a cloud of dust that surrounds this Pokemon while flying, while their flapping\
  \ produces a sound that resembles a woman singing."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Vibrava]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: ''
HomeSprite: SRD-flygon-HomeSprite.png
Image: flygon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Sonic Boom|Sonic Boom]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Amateur
  - '[[SRD-Sand Tomb|Sand Tomb]]'
- - Amateur
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Amateur
  - '[[SRD-Bide|Bide]]'
- - Amateur
  - '[[SRD-Supersonic|Supersonic]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Dragon Tail|Dragon Tail]]'
- - Amateur
  - '[[SRD-Earth Power|Earth Power]]'
- - Amateur
  - '[[SRD-Uproar|Uproar]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Ace
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Dragon Claw|Dragon Claw]]'
- - Ace
  - '[[SRD-Dragon Rush|Dragon Rush]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
- - Pro
  - '[[SRD-Draco Meteor|Draco Meteor]]'
Number: 330
ShuffleToken: SRD-flygon-ShuffleToken.png
Type1: Ground
Type2: Dragon
Weight:
  Kilograms: 82.0
  Pounds: 180.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-flygon-BookSprite.png|wsmall]]
> ![[SRD-flygon-HomeSprite.png]]
> ![[SRD-flygon-BoxSprite.png|htiny]]
> ![[SRD-flygon-ShuffleToken.png|wsmall]]


*Mystic Pokemon*
*Known as the “Elemental Spirit of the Desert”. Their wings create a cloud of dust that surrounds this Pokemon while flying, while their flapping produces a sound that resembles a woman singing.*

**DexID**:: 0330
**Name**:: Flygon
**Type**:: Ground / Dragon
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'6" / 2.0m
**Weight**: 180.8lbs / 82.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Vibrava]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Flygon.md"
flatten moves as T
where file.path = this.file.path
```
