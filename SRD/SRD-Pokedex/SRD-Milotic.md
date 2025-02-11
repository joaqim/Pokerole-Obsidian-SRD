---
Ability1: Marvel Scale
Ability2: Competitive
BookSprite: SRD-milotic-BookSprite.png
BoxSprite: SRD-milotic-BoxSprite.png
DexCategory: Tender Pokemon
DexDescription: Milotic is considered to be one of the most beautiful Pokemon in existence.
  It has inspired music, paintings and statues. It has the power to calm the anger
  and hostility of its foes.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Stat
  Pokemon: '[[SRD-Feebas]]'
  Stat: Beauty
  Value: 5
GenderType: ''
Height:
  Feet: 20.3
  Meters: 6.2
HiddenAbility: Cute Charm
HomeSprite: SRD-milotic-HomeSprite.png
Image: milotic.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - Starter
  - '[[SRD-Wrap|Wrap]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Sport|Water Sport]]'
- - Beginner
  - '[[SRD-Refresh|Refresh]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Amateur
  - '[[SRD-Twister|Twister]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Amateur
  - '[[SRD-Captivate|Captivate]]'
- - Amateur
  - '[[SRD-Dragon Tail|Dragon Tail]]'
- - Amateur
  - '[[SRD-Recover|Recover]]'
- - Amateur
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Amateur
  - '[[SRD-Attract|Attract]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Safeguard|Safeguard]]'
- - Ace
  - '[[SRD-Coil|Coil]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Rain Dance|Rain Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Pro
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Pro
  - '[[SRD-Magic Coat|Magic Coat]]'
Number: 350
ShuffleToken: SRD-milotic-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 162.0
  Pounds: 357.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-milotic-BookSprite.png|wsmall]]
> ![[SRD-milotic-HomeSprite.png]]
> ![[SRD-milotic-BoxSprite.png|htiny]]
> ![[SRD-milotic-ShuffleToken.png|wsmall]]


*Tender Pokemon*
*Milotic is considered to be one of the most beautiful Pokemon in existence. It has inspired music, paintings and statues. It has the power to calm the anger and hostility of its foes.*

**DexID**:: 0350
**Name**:: Milotic
**Type**:: Water
**Abilities**:: [[SRD-Marvel Scale|Marvel Scale]] / [[SRD-Competitive|Competitive]] ([[SRD-Cute Charm|Cute Charm]])
**Base HP**:: 7

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 20'3" / 6.2m
**Weight**: 357.1lbs / 162.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon        | Kind   | Stat   |   Value |
|:----------|:---------------|:-------|:-------|--------:|
| From      | [[SRD-Feebas]] | Stat   | Beauty |       5 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Milotic.md"
flatten moves as T
where file.path = this.file.path
```
