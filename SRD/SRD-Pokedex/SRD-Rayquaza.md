---
Ability1: Air Lock
Ability2: ''
BookSprite: SRD-rayquaza-BookSprite.png
BoxSprite: SRD-rayquaza-BoxSprite.png
DexCategory: No Data
DexDescription: The legend tells how Rayquaza lived in the outer layer of this world.
  It came to end the quarrel between Groudon and Kyogre, granted the world with blue
  skies and then left.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Pokeball
  Kind: Mega
  Pokemon: '[[SRD-Rayquaza (Mega Form)]]'
GenderType: N
Height:
  Feet: 23.0
  Meters: 7.0
HiddenAbility: ''
HomeSprite: SRD-rayquaza-HomeSprite.png
Image: rayquaza.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Twister|Twister]]'
- - Master
  - '[[SRD-Scary Face|Scary Face]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Crunch|Crunch]]'
- - Master
  - '[[SRD-Air Slash|Air Slash]]'
- - Master
  - '[[SRD-Rest|Rest]]'
- - Master
  - '[[SRD-Extreme Speed|Extreme Speed]]'
- - Master
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Master
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Master
  - '[[SRD-Fly|Fly]]'
- - Master
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Master
  - '[[SRD-Outrage|Outrage]]'
- - Master
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Master
  - '[[SRD-Roar|Roar]]'
- - Master
  - '[[SRD-Dragon Ascent|Dragon Ascent]]'
- - Master
  - '[[SRD-Sky Drop|Sky Drop]]'
- - Master
  - '[[SRD-Defog|Defog]]'
- - Master
  - '[[SRD-Tailwind|Tailwind]]'
- - Master
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Master
  - '[[SRD-Sunny Day|Sunny Day]]'
- - Master
  - '[[SRD-Dive|Dive]]'
- - Master
  - '[[SRD-Dig|Dig]]'
- - Master
  - '[[SRD-Draco Meteor|Draco Meteor]]'
- - Master
  - '[[SRD-Hurricane|Hurricane]]'
- - Master
  - '[[SRD-Cosmic Power|Cosmic Power]]'
Number: 384
ShuffleToken: SRD-rayquaza-ShuffleToken.png
Type1: Dragon
Type2: Flying
Weight:
  Kilograms: 206.5
  Pounds: 455.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-rayquaza-BookSprite.png|wsmall]]
> ![[SRD-rayquaza-HomeSprite.png]]
> ![[SRD-rayquaza-BoxSprite.png|htiny]]
> ![[SRD-rayquaza-ShuffleToken.png|wsmall]]


*No Data*
*The legend tells how Rayquaza lived in the outer layer of this world. It came to end the quarrel between Groudon and Kyogre, granted the world with blue skies and then left.*

**DexID**:: 0384
**Name**:: Rayquaza
**Type**:: Dragon / Flying
**Abilities**:: [[SRD-Air Lock|Air Lock]]
**Base HP**:: 8

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::8)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::8)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 23'0" / 7.0m
**Weight**: 455.3lbs / 206.5kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon                      | Kind   | Item     |
|:----------|:-----------------------------|:-------|:---------|
| To        | [[SRD-Rayquaza (Mega Form)]] | Mega   | Pokeball |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Rayquaza.md"
flatten moves as T
where file.path = this.file.path
```
