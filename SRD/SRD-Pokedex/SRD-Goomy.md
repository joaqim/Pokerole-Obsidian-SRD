---
Ability1: Sap Sipper
Ability2: Hydration
BookSprite: SRD-goomy-BookSprite.png
BoxSprite: SRD-goomy-BoxSprite.png
DexCategory: Soft Tissue Pokemon
DexDescription: "The weakest but best tempered Dragon Pokemon known. It lives in damp\
  \ and shady places, so its body doesn\u2019t dry out. It\u2019s covered in a slimy\
  \ membrane that makes things slide off of it."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Sliggoo]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Gooey
HomeSprite: SRD-goomy-HomeSprite.png
Image: goomy.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Bubble|Bubble]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - Beginner
  - '[[SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bide|Bide]]'
- - Amateur
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Amateur
  - '[[SRD-Rain Dance|Rain Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Flail|Flail]]'
- - Ace
  - '[[SRD-Body Slam|Body Slam]]'
- - Ace
  - '[[SRD-Muddy Water|Muddy Water]]'
- - Ace
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Pro
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Pro
  - '[[SRD-Counter|Counter]]'
Number: 704
ShuffleToken: SRD-goomy-ShuffleToken.png
Type1: Dragon
Type2: ''
Weight:
  Kilograms: 2.8
  Pounds: 6.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-goomy-BookSprite.png|wsmall]]
> ![[SRD-goomy-HomeSprite.png]]
> ![[SRD-goomy-BoxSprite.png|htiny]]
> ![[SRD-goomy-ShuffleToken.png|wsmall]]


*Soft Tissue Pokemon*
*The weakest but best tempered Dragon Pokemon known. It lives in damp and shady places, so its body doesn’t dry out. It’s covered in a slimy membrane that makes things slide off of it.*

**DexID**:: 0704
**Name**:: Goomy
**Type**:: Dragon
**Abilities**:: [[SRD-Sap Sipper|Sap Sipper]] / [[SRD-Hydration|Hydration]] ([[SRD-Gooey|Gooey]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 1'0" / 0.3m
**Weight**: 6.2lbs / 2.8kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Sliggoo]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Goomy.md"
flatten moves as T
where file.path = this.file.path
```
