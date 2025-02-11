---
Ability1: Swift Swim
Ability2: ''
BookSprite: SRD-swampert-mega-form-BookSprite.png
BoxSprite: SRD-swampert-mega-form-BoxSprite.png
DexCategory: Mud Fish Pokemon
DexDescription: The power of the Mega Stone increases its muscle strength, it would
  appear to be slower but its skin is so slippy it allows it to quickly slide over
  puddles and mud. It also becomes a bit bolder and moody.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Swampertite
  Kind: Mega
  Pokemon: '[[SRD-Swampert]]'
GenderType: ''
Height:
  Feet: 6.2
  Meters: 1.9
HiddenAbility: ''
HomeSprite: SRD-swampert-mega-form-HomeSprite.png
Image: swampert-mega-form.png
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
ShuffleToken: SRD-swampert-mega-form-ShuffleToken.png
Type1: Water
Type2: Ground
Weight:
  Kilograms: 102.0
  Pounds: 224.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-swampert-mega-form-BookSprite.png|wsmall]]
> ![[SRD-swampert-mega-form-HomeSprite.png]]
> ![[SRD-swampert-mega-form-BoxSprite.png|htiny]]
> ![[SRD-swampert-mega-form-ShuffleToken.png|wsmall]]


*Mud Fish Pokemon*
*The power of the Mega Stone increases its muscle strength, it would appear to be slower but its skin is so slippy it allows it to quickly slide over puddles and mud. It also becomes a bit bolder and moody.*

**DexID**:: 0260M1
**Name**:: Swampert (Mega Form)
**Type**:: Water / Ground
**Abilities**:: [[SRD-Swift Swim|Swift Swim]]
**Base HP**:: 7

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 6'2" / 1.9m
**Weight**: 224.9lbs / 102.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon          | Kind   | Item        |
|:----------|:-----------------|:-------|:------------|
| From      | [[SRD-Swampert]] | Mega   | Swampertite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Swampert (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
