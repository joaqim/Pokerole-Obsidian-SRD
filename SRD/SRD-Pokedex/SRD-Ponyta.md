---
Ability1: Run Away
Ability2: Flash Fire
BookSprite: SRD-ponyta-BookSprite.png
BoxSprite: SRD-ponyta-BoxSprite.png
DexCategory: Fire Horse Pokemon
DexDescription: "It\u2019s not very common to see one stay still for more than a few\
  \ seconds. Soon after it\u2019s born, its flames begin to burn. It is weak at first\
  \ but soon begins to develop a great speed chasing after its parents."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Rapidash]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Flame Body
HomeSprite: SRD-ponyta-HomeSprite.png
Image: ponyta.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Flame Wheel|Flame Wheel]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Amateur
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Amateur
  - '[[SRD-Stomp|Stomp]]'
- - Amateur
  - '[[SRD-Inferno|Inferno]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Agility|Agility]]'
- - Ace
  - '[[SRD-Fire Blast|Fire Blast]]'
- - Ace
  - '[[SRD-Bounce|Bounce]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Morning Sun|Morning Sun]]'
- - Pro
  - '[[SRD-Double Kick|Double Kick]]'
- - Pro
  - '[[SRD-Hypnosis|Hypnosis]]'
Number: 77
ShuffleToken: SRD-ponyta-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 30.0
  Pounds: 66.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-ponyta-BookSprite.png|wsmall]]
> ![[SRD-ponyta-HomeSprite.png]]
> ![[SRD-ponyta-BoxSprite.png|htiny]]
> ![[SRD-ponyta-ShuffleToken.png|wsmall]]


*Fire Horse Pokemon*
*It’s not very common to see one stay still for more than a few seconds. Soon after it’s born, its flames begin to burn. It is weak at first but soon begins to develop a great speed chasing after its parents.*

**DexID**:: 0077
**Name**:: Ponyta
**Type**:: Fire
**Abilities**:: [[SRD-Run Away|Run Away]] / [[SRD-Flash Fire|Flash Fire]] ([[SRD-Flame Body|Flame Body]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 66.1lbs / 30.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Rapidash]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Ponyta.md"
flatten moves as T
where file.path = this.file.path
```
