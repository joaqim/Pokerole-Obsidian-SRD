---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-fennekin-BookSprite.png
BoxSprite: SRD-fennekin-BoxSprite.png
DexCategory: Fox Pokemon
DexDescription: This small and elusive Pokemon intimidates opponents by puffing hot
  air out of its ears. It likes to keep twigs and sticks nearby to munch them instead
  of snacks. They make good pets but they are pretty rare.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Braixen]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Magician
HomeSprite: SRD-fennekin-HomeSprite.png
Image: fennekin.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Howl|Howl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Amateur
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Psyshock|Psyshock]]'
- - Amateur
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Amateur
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Sunny Day|Sunny Day]]'
- - Ace
  - '[[SRD-Magic Room|Magic Room]]'
- - Ace
  - '[[SRD-Fire Blast|Fire Blast]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Pro
  - '[[SRD-Wish|Wish]]'
- - Pro
  - '[[SRD-Fire Pledge|Fire Pledge]]'
Number: 653
ShuffleToken: SRD-fennekin-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 9.4
  Pounds: 20.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-fennekin-BookSprite.png|wsmall]]
> ![[SRD-fennekin-HomeSprite.png]]
> ![[SRD-fennekin-BoxSprite.png|htiny]]
> ![[SRD-fennekin-ShuffleToken.png|wsmall]]


*Fox Pokemon*
*This small and elusive Pokemon intimidates opponents by puffing hot air out of its ears. It likes to keep twigs and sticks nearby to munch them instead of snacks. They make good pets but they are pretty rare.*

**DexID**:: 0653
**Name**:: Fennekin
**Type**:: Fire
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Magician|Magician]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 20.7lbs / 9.4kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Braixen]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Fennekin.md"
flatten moves as T
where file.path = this.file.path
```
