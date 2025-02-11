---
Ability1: Shed Skin
Ability2: ''
BookSprite: SRD-dratini-BookSprite.png
BoxSprite: SRD-dratini-BoxSprite.png
DexCategory: Dragon Pokemon
DexDescription: Up until recently its existence was debated as being a mere legend,
  then a small colony was found underwater. It is still extremely rare to find. It
  sheds skin and grows larger every day.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Dragonair]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: Marvel Scale
HomeSprite: SRD-dratini-HomeSprite.png
Image: dratini.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Wrap|Wrap]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Beginner
  - '[[SRD-Twister|Twister]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Dragon Tail|Dragon Tail]]'
- - Amateur
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Amateur
  - '[[SRD-Dragon Rush|Dragon Rush]]'
- - Amateur
  - '[[SRD-Safeguard|Safeguard]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Ace
  - '[[SRD-Outrage|Outrage]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Pro
  - '[[SRD-Extreme Speed|Extreme Speed]]'
- - Pro
  - '[[SRD-Mist|Mist]]'
Number: 147
ShuffleToken: SRD-dratini-ShuffleToken.png
Type1: Dragon
Type2: ''
Weight:
  Kilograms: 3.3
  Pounds: 7.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dratini-BookSprite.png|wsmall]]
> ![[SRD-dratini-HomeSprite.png]]
> ![[SRD-dratini-BoxSprite.png|htiny]]
> ![[SRD-dratini-ShuffleToken.png|wsmall]]


*Dragon Pokemon*
*Up until recently its existence was debated as being a mere legend, then a small colony was found underwater. It is still extremely rare to find. It sheds skin and grows larger every day.*

**DexID**:: 0147
**Name**:: Dratini
**Type**:: Dragon
**Abilities**:: [[SRD-Shed Skin|Shed Skin]] ([[SRD-Marvel Scale|Marvel Scale]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 5'9" / 1.8m
**Weight**: 7.3lbs / 3.3kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Dragonair]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Dratini.md"
flatten moves as T
where file.path = this.file.path
```
