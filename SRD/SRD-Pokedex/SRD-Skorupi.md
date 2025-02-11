---
Ability1: Battle Armor
Ability2: Sniper
BookSprite: SRD-skorupi-BookSprite.png
BoxSprite: SRD-skorupi-BoxSprite.png
DexCategory: Scorpion Pokemon
DexDescription: It lives in deserts and arid regions. It buries itself under the sand,
  waiting for an unsuspecting prey to come nearby. It will then sting the prey and
  cling to it tenaciously until the poison takes effect.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Drapion]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Keen Eye
HomeSprite: SRD-skorupi-HomeSprite.png
Image: skorupi.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bite|Bite]]'
- - Starter
  - '[[SRD-Poison Sting|Poison Sting]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Knock Off|Knock Off]]'
- - Beginner
  - '[[SRD-Pin Missile|Pin Missile]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Acupressure|Acupressure]]'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[SRD-Poison Fang|Poison Fang]]'
- - Amateur
  - '[[SRD-Venoshock|Venoshock]]'
- - Amateur
  - '[[SRD-Hone Claws|Hone Claws]]'
- - Amateur
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Scary Face|Scary Face]]'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Fell Stinger|Fell Stinger]]'
- - Ace
  - '[[SRD-Cross Poison|Cross Poison]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Agility|Agility]]'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Poison Tail|Poison Tail]]'
Number: 451
ShuffleToken: SRD-skorupi-ShuffleToken.png
Type1: Poison
Type2: Bug
Weight:
  Kilograms: 12.0
  Pounds: 26.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-skorupi-BookSprite.png|wsmall]]
> ![[SRD-skorupi-HomeSprite.png]]
> ![[SRD-skorupi-BoxSprite.png|htiny]]
> ![[SRD-skorupi-ShuffleToken.png|wsmall]]


*Scorpion Pokemon*
*It lives in deserts and arid regions. It buries itself under the sand, waiting for an unsuspecting prey to come nearby. It will then sting the prey and cling to it tenaciously until the poison takes effect.*

**DexID**:: 0451
**Name**:: Skorupi
**Type**:: Poison / Bug
**Abilities**:: [[SRD-Battle Armor|Battle Armor]] / [[SRD-Sniper|Sniper]] ([[SRD-Keen Eye|Keen Eye]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 26.5lbs / 12.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Drapion]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Skorupi.md"
flatten moves as T
where file.path = this.file.path
```
