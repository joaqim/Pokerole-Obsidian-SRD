---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-chingling-BookSprite.png
BoxSprite: SRD-chingling-BoxSprite.png
DexCategory: Bell Pokemon
DexDescription: It has a ball inside its mouth that makes a ringing sound when it
  hops around. To defend itself, it will emit low frequency cries that deafen its
  foes. However this sound is not audible to humans.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Stat
  Pokemon: '[[SRD-Chimecho]]'
  Stat: Happiness
  Value: 4
GenderType: ''
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: ''
HomeSprite: SRD-chingling-HomeSprite.png
Image: chingling.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Wrap|Wrap]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Yawn|Yawn]]'
- - Amateur
  - '[[SRD-Confusion|Confusion]]'
- - Amateur
  - '[[SRD-Uproar|Uproar]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[SRD-Entrainment|Entrainment]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Pro
  - '[[SRD-Recover|Recover]]'
- - Pro
  - '[[SRD-Future Sight|Future Sight]]'
Number: 433
ShuffleToken: SRD-chingling-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 0.6
  Pounds: 1.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-chingling-BookSprite.png|wsmall]]
> ![[SRD-chingling-HomeSprite.png]]
> ![[SRD-chingling-BoxSprite.png|htiny]]
> ![[SRD-chingling-ShuffleToken.png|wsmall]]


*Bell Pokemon*
*It has a ball inside its mouth that makes a ringing sound when it hops around. To defend itself, it will emit low frequency cries that deafen its foes. However this sound is not audible to humans.*

**DexID**:: 0433
**Name**:: Chingling
**Type**:: Psychic
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 0'7" / 0.2m
**Weight**: 1.3lbs / 0.6kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon          | Kind   | Stat      |   Value |
|:----------|:-----------------|:-------|:----------|--------:|
| To        | [[SRD-Chimecho]] | Stat   | Happiness |       4 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Chingling.md"
flatten moves as T
where file.path = this.file.path
```
