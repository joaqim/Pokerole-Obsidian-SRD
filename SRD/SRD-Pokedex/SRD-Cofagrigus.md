---
Ability1: Mummy
Ability2: ''
BookSprite: SRD-cofagrigus-BookSprite.png
BoxSprite: SRD-cofagrigus-BoxSprite.png
DexCategory: Coffin Pokemon
DexDescription: This Pokemon has only been seen few times in the ruins and tombs of
  ancient civilizations. It curses and transforms people and Pokemon into mummy-like
  creatures. It is said it feeds on pure gold.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Yamask]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: ''
HomeSprite: SRD-cofagrigus-HomeSprite.png
Image: cofagrigus.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Disable|Disable]]'
- - Beginner
  - '[[SRD-Haze|Haze]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Night Shade|Night Shade]]'
- - Amateur
  - '[[SRD-Hex|Hex]]'
- - Amateur
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - Amateur
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Power Split|Power Split]]'
- - Amateur
  - '[[SRD-Guard Split|Guard Split]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Ace
  - '[[SRD-Grudge|Grudge]]'
- - Ace
  - '[[SRD-Mean Look|Mean Look]]'
- - Ace
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Imprison|Imprison]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Heal Block|Heal Block]]'
Number: 563
ShuffleToken: SRD-cofagrigus-ShuffleToken.png
Type1: Ghost
Type2: ''
Weight:
  Kilograms: 76.5
  Pounds: 168.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cofagrigus-BookSprite.png|wsmall]]
> ![[SRD-cofagrigus-HomeSprite.png]]
> ![[SRD-cofagrigus-BoxSprite.png|htiny]]
> ![[SRD-cofagrigus-ShuffleToken.png|wsmall]]


*Coffin Pokemon*
*This Pokemon has only been seen few times in the ruins and tombs of ancient civilizations. It curses and transforms people and Pokemon into mummy-like creatures. It is said it feeds on pure gold.*

**DexID**:: 0563
**Name**:: Cofagrigus
**Type**:: Ghost
**Abilities**:: [[SRD-Mummy|Mummy]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::4)/(MaxVitality::8)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'6" / 1.7m
**Weight**: 168.7lbs / 76.5kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Yamask]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Cofagrigus.md"
flatten moves as T
where file.path = this.file.path
```
