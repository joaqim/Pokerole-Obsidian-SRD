---
Ability1: Magic Bounce
Ability2: ''
BookSprite: SRD-absol-mega-form-BookSprite.png
BoxSprite: SRD-absol-mega-form-BoxSprite.png
DexCategory: Disaster Pokemon
DexDescription: The power of the Mega Stone makes its fur elongate. What you see are
  not wings, just puffs of hair. It gets distressed by this form and dislikes going
  into fights, so it uses its intimidating aura to fend off foes.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Absolite
  Kind: Mega
  Pokemon: '[[SRD-Absol]]'
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: ''
HomeSprite: SRD-absol-mega-form-HomeSprite.png
Image: absol-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Detect|Detect]]'
- - Starter
  - '[[SRD-Taunt|Taunt]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - Beginner
  - '[[SRD-Razor Wind|Razor Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Me First|Me First]]'
- - Amateur
  - '[[SRD-Feint|Feint]]'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Double Team|Double Team]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Amateur
  - '[[SRD-Future Sight|Future Sight]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Psycho Cut|Psycho Cut]]'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Perish Song|Perish Song]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Hex|Hex]]'
- - Pro
  - '[[SRD-Play Rough|Play Rough]]'
- - Pro
  - '[[SRD-Spite|Spite]]'
Number: 359
ShuffleToken: SRD-absol-mega-form-ShuffleToken.png
Type1: Dark
Type2: ''
Weight:
  Kilograms: 49.0
  Pounds: 108.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-absol-mega-form-BookSprite.png|wsmall]]
> ![[SRD-absol-mega-form-HomeSprite.png]]
> ![[SRD-absol-mega-form-BoxSprite.png|htiny]]
> ![[SRD-absol-mega-form-ShuffleToken.png|wsmall]]


*Disaster Pokemon*
*The power of the Mega Stone makes its fur elongate. What you see are not wings, just puffs of hair. It gets distressed by this form and dislikes going into fights, so it uses its intimidating aura to fend off foes.*

**DexID**:: 0359M1
**Name**:: Absol (Mega Form)
**Type**:: Dark
**Abilities**:: [[SRD-Magic Bounce|Magic Bounce]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'9" / 1.2m
**Weight**: 108.0lbs / 49.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon       | Kind   | Item     |
|:----------|:--------------|:-------|:---------|
| From      | [[SRD-Absol]] | Mega   | Absolite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Absol (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
