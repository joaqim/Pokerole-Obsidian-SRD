---
Ability1: Cute Charm
Ability2: ''
BookSprite: SRD-sylveon-BookSprite.png
BoxSprite: SRD-sylveon-BoxSprite.png
DexCategory: Intertwining Pokemon
DexDescription: This rare and adorable Pokemon emanates a soothing aura to calm disturbances.
  It is said that only the Trainers who form an unbreakable bond with their Eevee
  can ever see this Pokemon.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Stat
  Pokemon: '[[SRD-Eevee]]'
  Stat: Loyalty
  Value: 5
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Pixilate
HomeSprite: SRD-sylveon-HomeSprite.png
Image: sylveon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Beginner
  - '[[SRD-Fairy Wind|Fairy Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - Amateur
  - '[[SRD-Skill Swap|Skill Swap]]'
- - Amateur
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Moonblast|Moonblast]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[SRD-Psych Up|Psych Up]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Captivate|Captivate]]'
- - Pro
  - '[[SRD-Wish|Wish]]'
- - Pro
  - '[[SRD-Hyper Voice|Hyper Voice]]'
Number: 700
ShuffleToken: SRD-sylveon-ShuffleToken.png
Type1: Fairy
Type2: ''
Weight:
  Kilograms: 23.5
  Pounds: 51.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sylveon-BookSprite.png|wsmall]]
> ![[SRD-sylveon-HomeSprite.png]]
> ![[SRD-sylveon-BoxSprite.png|htiny]]
> ![[SRD-sylveon-ShuffleToken.png|wsmall]]


*Intertwining Pokemon*
*This rare and adorable Pokemon emanates a soothing aura to calm disturbances. It is said that only the Trainers who form an unbreakable bond with their Eevee can ever see this Pokemon.*

**DexID**:: 0700
**Name**:: Sylveon
**Type**:: Fairy
**Abilities**:: [[SRD-Cute Charm|Cute Charm]] ([[SRD-Pixilate|Pixilate]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 3'3" / 1.0m
**Weight**: 51.8lbs / 23.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon       | Kind   | Stat    |   Value |
|:----------|:--------------|:-------|:--------|--------:|
| From      | [[SRD-Eevee]] | Stat   | Loyalty |       5 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Sylveon.md"
flatten moves as T
where file.path = this.file.path
```
