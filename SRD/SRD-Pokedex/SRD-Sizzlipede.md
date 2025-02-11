---
Ability1: Flash Fire
Ability2: White Smoke
BookSprite: SRD-sizzlipede-BookSprite.png
BoxSprite: SRD-sizzlipede-BoxSprite.png
DexCategory: Radiator Pokemon
DexDescription: It stores flammable gas in its body and uses it to generate heat.
  The yellow sections on its belly get very hot. It wraps prey with its body heated
  to cook them, the it nibbles them down until nothing remains.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Centiskorch]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Flame Body
HomeSprite: SRD-sizzlipede-HomeSprite.png
Image: sizzlipede.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Ember|Ember]]'
- - Starter
  - '[[SRD-Smokescreen|Smokescreen]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Wrap|Wrap]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Flame Wheel|Flame Wheel]]'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[SRD-Coil|Coil]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Fire Spin|Fire Spin]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Fire Lash|Fire Lash]]'
- - Ace
  - '[[SRD-Lunge|Lunge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Burn Up|Burn Up]]'
- - Pro
  - '[[SRD-Knock Off|Knock Off]]'
- - Pro
  - '[[SRD-Struggle Bug|Struggle Bug]]'
- - Pro
  - '[[SRD-Venoshock|Venoshock]]'
Number: 850
ShuffleToken: SRD-sizzlipede-ShuffleToken.png
Type1: Fire
Type2: Bug
Weight:
  Kilograms: 1.0
  Pounds: 2.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sizzlipede-BookSprite.png|wsmall]]
> ![[SRD-sizzlipede-HomeSprite.png]]
> ![[SRD-sizzlipede-BoxSprite.png|htiny]]
> ![[SRD-sizzlipede-ShuffleToken.png|wsmall]]


*Radiator Pokemon*
*It stores flammable gas in its body and uses it to generate heat. The yellow sections on its belly get very hot. It wraps prey with its body heated to cook them, the it nibbles them down until nothing remains.*

**DexID**:: 0850
**Name**:: Sizzlipede
**Type**:: Fire / Bug
**Abilities**:: [[SRD-Flash Fire|Flash Fire]] / [[SRD-White Smoke|White Smoke]] ([[SRD-Flame Body|Flame Body]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'3" / 0.7m
**Weight**: 2.2lbs / 1.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon             | Kind   | Speed   |
|:----------|:--------------------|:-------|:--------|
| To        | [[SRD-Centiskorch]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Sizzlipede.md"
flatten moves as T
where file.path = this.file.path
```
