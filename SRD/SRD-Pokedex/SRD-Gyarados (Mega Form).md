---
Ability1: Mold Breaker
Ability2: ''
BookSprite: SRD-gyarados-mega-form-BookSprite.png
BoxSprite: SRD-gyarados-mega-form-BoxSprite.png
DexCategory: Atrocious Pokemon
DexDescription: With the power of the Mega Stone its body suffers a lot of strain,
  making it faster and stronger but also angrier and uncontrollable. It must have
  a strong bond or it will fall into a destructive rampage.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Gyaradosite
  Kind: Mega
  Pokemon: '[[SRD-Gyarados]]'
GenderType: ''
Height:
  Feet: 21.3
  Meters: 6.5
HiddenAbility: ''
HomeSprite: SRD-gyarados-mega-form-HomeSprite.png
Image: gyarados-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Twister|Twister]]'
- - Beginner
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Beginner
  - '[[SRD-Scary Face|Scary Face]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Hurricane|Hurricane]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Thrash|Thrash]]'
- - Amateur
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Amateur
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
- - Pro
  - '[[SRD-Bounce|Bounce]]'
Number: 130
ShuffleToken: SRD-gyarados-mega-form-ShuffleToken.png
Type1: Water
Type2: Dark
Weight:
  Kilograms: 305.0
  Pounds: 672.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gyarados-mega-form-BookSprite.png|wsmall]]
> ![[SRD-gyarados-mega-form-HomeSprite.png]]
> ![[SRD-gyarados-mega-form-BoxSprite.png|htiny]]
> ![[SRD-gyarados-mega-form-ShuffleToken.png|wsmall]]


*Atrocious Pokemon*
*With the power of the Mega Stone its body suffers a lot of strain, making it faster and stronger but also angrier and uncontrollable. It must have a strong bond or it will fall into a destructive rampage.*

**DexID**:: 0130M1
**Name**:: Gyarados (Mega Form)
**Type**:: Water / Dark
**Abilities**:: [[SRD-Mold Breaker|Mold Breaker]]
**Base HP**:: 8

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 21'3" / 6.5m
**Weight**: 672.4lbs / 305.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon          | Kind   | Item        |
|:----------|:-----------------|:-------|:------------|
| From      | [[SRD-Gyarados]] | Mega   | Gyaradosite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Gyarados (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
