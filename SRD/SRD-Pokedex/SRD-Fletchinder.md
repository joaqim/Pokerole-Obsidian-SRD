---
Ability1: Flame Body
Ability2: ''
BookSprite: SRD-fletchinder-BookSprite.png
BoxSprite: SRD-fletchinder-BoxSprite.png
DexCategory: Ember Pokemon
DexDescription: From its beak, it expels embers to set tall grass on fire, then it
  pounces on the bewildered prey that pop out of the grass. Its body becomes engulfed
  in flames when it starts to battle. It is a fierce Pokemon.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Fletchling]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Talonflame]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Gale Wings
HomeSprite: SRD-fletchinder-HomeSprite.png
Image: fletchinder.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Peck|Peck]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Ember|Ember]]'
- - Amateur
  - '[[SRD-Roost|Roost]]'
- - Amateur
  - '[[SRD-Razor Wind|Razor Wind]]'
- - Amateur
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Acrobatics|Acrobatics]]'
- - Ace
  - '[[SRD-Me First|Me First]]'
- - Ace
  - '[[SRD-Tailwind|Tailwind]]'
- - Ace
  - '[[SRD-Steel Wing|Steel Wing]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Snatch|Snatch]]'
- - Pro
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Pro
  - '[[SRD-Air Cutter|Air Cutter]]'
Number: 662
ShuffleToken: SRD-fletchinder-ShuffleToken.png
Type1: Fire
Type2: Flying
Weight:
  Kilograms: 16.0
  Pounds: 35.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-fletchinder-BookSprite.png|wsmall]]
> ![[SRD-fletchinder-HomeSprite.png]]
> ![[SRD-fletchinder-BoxSprite.png|htiny]]
> ![[SRD-fletchinder-ShuffleToken.png|wsmall]]


*Ember Pokemon*
*From its beak, it expels embers to set tall grass on fire, then it pounces on the bewildered prey that pop out of the grass. Its body becomes engulfed in flames when it starts to battle. It is a fierce Pokemon.*

**DexID**:: 0662
**Name**:: Fletchinder
**Type**:: Fire / Flying
**Abilities**:: [[SRD-Flame Body|Flame Body]] ([[SRD-Gale Wings|Gale Wings]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'3" / 0.7m
**Weight**: 35.3lbs / 16.0kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| From      | [[SRD-Fletchling]] | Level  | Medium  |
| To        | [[SRD-Talonflame]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Fletchinder.md"
flatten moves as T
where file.path = this.file.path
```
