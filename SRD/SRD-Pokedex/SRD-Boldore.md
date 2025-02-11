---
Ability1: Sturdy
Ability2: Weak Armor
BookSprite: SRD-boldore-BookSprite.png
BoxSprite: SRD-boldore-BoxSprite.png
DexCategory: Ore Pokemon
DexDescription: It releases the excess of energy in the form of red crystals. It is
  still blind, it looks for for water sources inside underground caves by using echo
  location. It is a pacific creature that keeps to itself most of the time.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Roggenrola]]'
  Speed: Medium
- Evolves: To
  Kind: Trade
  Pokemon: '[[SRD-Gigalith]]'
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Sand Force
HomeSprite: SRD-boldore-HomeSprite.png
Image: boldore.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Headbutt|Headbutt]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Amateur
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Smack Down|Smack Down]]'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Autotomize|Autotomize]]'
- - Pro
  - '[[SRD-Magnitude|Magnitude]]'
- - Pro
  - '[[SRD-Wide Guard|Wide Guard]]'
Number: 525
ShuffleToken: SRD-boldore-ShuffleToken.png
Type1: Rock
Type2: ''
Weight:
  Kilograms: 102.0
  Pounds: 224.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-boldore-BookSprite.png|wsmall]]
> ![[SRD-boldore-HomeSprite.png]]
> ![[SRD-boldore-BoxSprite.png|htiny]]
> ![[SRD-boldore-ShuffleToken.png|wsmall]]


*Ore Pokemon*
*It releases the excess of energy in the form of red crystals. It is still blind, it looks for for water sources inside underground caves by using echo location. It is a pacific creature that keeps to itself most of the time.*

**DexID**:: 0525
**Name**:: Boldore
**Type**:: Rock
**Abilities**:: [[SRD-Sturdy|Sturdy]] / [[SRD-Weak Armor|Weak Armor]] ([[SRD-Sand Force|Sand Force]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 3'0" / 0.9m
**Weight**: 224.9lbs / 102.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| From      | [[SRD-Roggenrola]] | Level  | Medium  |
| To        | [[SRD-Gigalith]]   | Trade  |         |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Boldore.md"
flatten moves as T
where file.path = this.file.path
```
