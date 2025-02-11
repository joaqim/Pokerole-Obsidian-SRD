---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-misdreavus-BookSprite.png
BoxSprite: SRD-misdreavus-BoxSprite.png
DexCategory: Screech Pokemon
DexDescription: Misdreavus frightens people with a creepy, sobbing cry. It uses the
  red spheres on its neck to absorb fear as nutrition. It takes a wicked pleasure
  in startling and scaring people.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Dusk Stone
  Kind: Stone
  Pokemon: '[[SRD-Mismagius]]'
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: ''
HomeSprite: SRD-misdreavus-HomeSprite.png
Image: misdreavus.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Psywave|Psywave]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Spite|Spite]]'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Mean Look|Mean Look]]'
- - Amateur
  - '[[SRD-Hex|Hex]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Pain Split|Pain Split]]'
- - Amateur
  - '[[SRD-Payback|Payback]]'
- - Amateur
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Perish Song|Perish Song]]'
- - Ace
  - '[[SRD-Grudge|Grudge]]'
- - Ace
  - '[[SRD-Power Gem|Power Gem]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Pro
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Pro
  - '[[SRD-Nasty Plot|Nasty Plot]]'
Number: 200
ShuffleToken: SRD-misdreavus-ShuffleToken.png
Type1: Ghost
Type2: ''
Weight:
  Kilograms: 1.0
  Pounds: 2.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-misdreavus-BookSprite.png|wsmall]]
> ![[SRD-misdreavus-HomeSprite.png]]
> ![[SRD-misdreavus-BoxSprite.png|htiny]]
> ![[SRD-misdreavus-ShuffleToken.png|wsmall]]


*Screech Pokemon*
*Misdreavus frightens people with a creepy, sobbing cry. It uses the red spheres on its neck to absorb fear as nutrition. It takes a wicked pleasure in startling and scaring people.*

**DexID**:: 0200
**Name**:: Misdreavus
**Type**:: Ghost
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'3" / 0.7m
**Weight**: 2.2lbs / 1.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Item       |
|:----------|:------------------|:-------|:-----------|
| To        | [[SRD-Mismagius]] | Stone  | Dusk Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Misdreavus.md"
flatten moves as T
where file.path = this.file.path
```
