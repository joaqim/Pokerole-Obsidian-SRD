---
Ability1: Torrent
Ability2: ''
BookSprite: SRD-swampert-BookSprite.png
BoxSprite: SRD-swampert-BoxSprite.png
DexCategory: Mud Fish Pokemon
DexDescription: They have an incredible sight that allows them to see in muddy water.
  They nest in beaches, and shield their young with their strong arms. When a storm
  is coming, Swamperts build a fort with big rocks.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Marshtomp]]'
  Speed: Medium
- Evolves: To
  Item: Swampertite
  Kind: Mega
  Pokemon: '[[SRD-Swampert (Mega Form)]]'
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Damp
HomeSprite: SRD-swampert-HomeSprite.png
Image: swampert.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Bide|Bide]]'
- - Amateur
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Amateur
  - '[[SRD-Foresight|Foresight]]'
- - Amateur
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Muddy Water|Muddy Water]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Ace
  - '[[SRD-Protect|Protect]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Endeavor|Endeavor]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Pro
  - '[[SRD-Hydro Cannon|Hydro Cannon]]'
- - Pro
  - '[[SRD-Avalanche|Avalanche]]'
Number: 260
ShuffleToken: SRD-swampert-ShuffleToken.png
Type1: Water
Type2: Ground
Weight:
  Kilograms: 81.9
  Pounds: 180.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-swampert-BookSprite.png|wsmall]]
> ![[SRD-swampert-HomeSprite.png]]
> ![[SRD-swampert-BoxSprite.png|htiny]]
> ![[SRD-swampert-ShuffleToken.png|wsmall]]


*Mud Fish Pokemon*
*They have an incredible sight that allows them to see in muddy water. They nest in beaches, and shield their young with their strong arms. When a storm is coming, Swamperts build a fort with big rocks.*

**DexID**:: 0260
**Name**:: Swampert
**Type**:: Water / Ground
**Abilities**:: [[SRD-Torrent|Torrent]] ([[SRD-Damp|Damp]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 180.6lbs / 81.9kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                      | Kind   | Speed   | Item        |
|:----------|:-----------------------------|:-------|:--------|:------------|
| From      | [[SRD-Marshtomp]]            | Level  | Medium  |             |
| To        | [[SRD-Swampert (Mega Form)]] | Mega   |         | Swampertite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Swampert.md"
flatten moves as T
where file.path = this.file.path
```
