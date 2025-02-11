---
Ability1: Frisk
Ability2: Infiltrator
BookSprite: SRD-noibat-BookSprite.png
BoxSprite: SRD-noibat-BoxSprite.png
DexCategory: Sound Wave Pokemon
DexDescription: They live in dark caves and use echolocation to move around. Their
  enormous ears can emit ultrasonic waves that cause dizziness. Groups of them can
  even take on prey several times their size.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Noivern]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Telepathy
HomeSprite: SRD-noibat-HomeSprite.png
Image: noibat.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Screech|Screech]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Supersonic|Supersonic]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - Beginner
  - '[[SRD-Gust|Gust]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Wing Attack|Wing Attack]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Air Cutter|Air Cutter]]'
- - Amateur
  - '[[SRD-Roost|Roost]]'
- - Amateur
  - '[[SRD-Razor Wind|Razor Wind]]'
- - Amateur
  - '[[SRD-Tailwind|Tailwind]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Ace
  - '[[SRD-Super Fang|Super Fang]]'
- - Ace
  - '[[SRD-Air Slash|Air Slash]]'
- - Ace
  - '[[SRD-Hurricane|Hurricane]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Super Fang|Super Fang]]'
- - Pro
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
Number: 714
ShuffleToken: SRD-noibat-ShuffleToken.png
Type1: Flying
Type2: Dragon
Weight:
  Kilograms: 8.0
  Pounds: 17.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-noibat-BookSprite.png|wsmall]]
> ![[SRD-noibat-HomeSprite.png]]
> ![[SRD-noibat-BoxSprite.png|htiny]]
> ![[SRD-noibat-ShuffleToken.png|wsmall]]


*Sound Wave Pokemon*
*They live in dark caves and use echolocation to move around. Their enormous ears can emit ultrasonic waves that cause dizziness. Groups of them can even take on prey several times their size.*

**DexID**:: 0714
**Name**:: Noibat
**Type**:: Flying / Dragon
**Abilities**:: [[SRD-Frisk|Frisk]] / [[SRD-Infiltrator|Infiltrator]] ([[SRD-Telepathy|Telepathy]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'6" / 0.5m
**Weight**: 17.6lbs / 8.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Noivern]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Noibat.md"
flatten moves as T
where file.path = this.file.path
```
