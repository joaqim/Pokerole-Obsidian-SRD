---
Ability1: Ball Fetch
Ability2: ''
BookSprite: SRD-yamper-BookSprite.png
BoxSprite: SRD-yamper-BoxSprite.png
DexCategory: Puppy Pokemon
DexDescription: Its energy and big smile make this Pokemon very popular as a herding
  dog. When it runs, it generates electricity from the base of its tail. It loves
  to fetch balls and if you give it some treats it will love you forever.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Boltund]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Rattled
HomeSprite: SRD-yamper-HomeSprite.png
Image: yamper.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Nuzzle|Nuzzle]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Charm|Charm]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Charge|Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Wild Charge|Wild Charge]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Pro
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Pro
  - '[[SRD-Howl|Howl]]'
Number: 835
ShuffleToken: SRD-yamper-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 13.5
  Pounds: 29.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-yamper-BookSprite.png|wsmall]]
> ![[SRD-yamper-HomeSprite.png]]
> ![[SRD-yamper-BoxSprite.png|htiny]]
> ![[SRD-yamper-ShuffleToken.png|wsmall]]


*Puppy Pokemon*
*Its energy and big smile make this Pokemon very popular as a herding dog. When it runs, it generates electricity from the base of its tail. It loves to fetch balls and if you give it some treats it will love you forever.*

**DexID**:: 0835
**Name**:: Yamper
**Type**:: Electric
**Abilities**:: [[SRD-Ball Fetch|Ball Fetch]] ([[SRD-Rattled|Rattled]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'0" / 0.3m
**Weight**: 29.8lbs / 13.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Boltund]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Yamper.md"
flatten moves as T
where file.path = this.file.path
```
