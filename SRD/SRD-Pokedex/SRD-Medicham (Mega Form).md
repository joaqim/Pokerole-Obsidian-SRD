---
Ability1: Pure Power
Ability2: ''
BookSprite: SRD-medicham-mega-form-BookSprite.png
BoxSprite: SRD-medicham-mega-form-BoxSprite.png
DexCategory: Meditate Pokemon
DexDescription: The power of the Mega Stone is tempered thanks to its meditation skills.
  This makes it increase all of its capabilities but not as much as other mega-evolutions,
  all in favor of keeping control of its senses.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Medichamite
  Kind: Mega
  Pokemon: '[[SRD-Medicham]]'
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: ''
HomeSprite: SRD-medicham-mega-form-HomeSprite.png
Image: medicham-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bide|Bide]]'
- - Starter
  - '[[SRD-Detect|Detect]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Meditate|Meditate]]'
- - Beginner
  - '[[SRD-Endure|Endure]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Amateur
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Amateur
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Amateur
  - '[[SRD-Mind Reader|Mind Reader]]'
- - Amateur
  - '[[SRD-Feint|Feint]]'
- - Amateur
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Amateur
  - '[[SRD-Force Palm|Force Palm]]'
- - Amateur
  - '[[SRD-High Jump Kick|High Jump Kick]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psych Up|Psych Up]]'
- - Ace
  - '[[SRD-Acupressure|Acupressure]]'
- - Ace
  - '[[SRD-Power Trick|Power Trick]]'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - Ace
  - '[[SRD-Recover|Recover]]'
- - Ace
  - '[[SRD-Counter|Counter]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Pro
  - '[[SRD-Gravity|Gravity]]'
- - Pro
  - '[[SRD-Baton Pass|Baton Pass]]'
Number: 308
ShuffleToken: SRD-medicham-mega-form-ShuffleToken.png
Type1: Fighting
Type2: Psychic
Weight:
  Kilograms: 31.5
  Pounds: 69.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-medicham-mega-form-BookSprite.png|wsmall]]
> ![[SRD-medicham-mega-form-HomeSprite.png]]
> ![[SRD-medicham-mega-form-BoxSprite.png|htiny]]
> ![[SRD-medicham-mega-form-ShuffleToken.png|wsmall]]


*Meditate Pokemon*
*The power of the Mega Stone is tempered thanks to its meditation skills. This makes it increase all of its capabilities but not as much as other mega-evolutions, all in favor of keeping control of its senses.*

**DexID**:: 0308M1
**Name**:: Medicham (Mega Form)
**Type**:: Fighting / Psychic
**Abilities**:: [[SRD-Pure Power|Pure Power]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'3" / 1.3m
**Weight**: 69.4lbs / 31.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Item        |
|:----------|:-----------------|:-------|:------------|
| From      | [[SRD-Medicham]] | Mega   | Medichamite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Medicham (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
