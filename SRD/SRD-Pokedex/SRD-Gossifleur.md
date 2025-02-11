---
Ability1: Cotton Down
Ability2: Regenerator
BookSprite: SRD-gossifleur-BookSprite.png
BoxSprite: SRD-gossifleur-BoxSprite.png
DexCategory: Flowering Pokemon
DexDescription: "You\u2019ll find them in fields, basking in the sun, they let the\
  \ wind sway them while they sing a joyful song. Afterwards their flowers bloom and\
  \ glow. This delightful display makes it very popular among Trainers."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Eldegoss]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Effect Spore
HomeSprite: SRD-gossifleur-HomeSprite.png
Image: gossifleur.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leafage|Leafage]]'
- - Starter
  - '[[SRD-Sing|Sing]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Beginner
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Round|Round]]'
- - Amateur
  - '[[SRD-Leaf Tornado|Leaf Tornado]]'
- - Amateur
  - '[[SRD-Synthesis|Synthesis]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Ace
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Ace
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Growth|Growth]]'
- - Pro
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Pro
  - '[[SRD-Poison Powder|Poison Powder]]'
Number: 829
ShuffleToken: SRD-gossifleur-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 2.2
  Pounds: 4.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gossifleur-BookSprite.png|wsmall]]
> ![[SRD-gossifleur-HomeSprite.png]]
> ![[SRD-gossifleur-BoxSprite.png|htiny]]
> ![[SRD-gossifleur-ShuffleToken.png|wsmall]]


*Flowering Pokemon*
*You’ll find them in fields, basking in the sun, they let the wind sway them while they sing a joyful song. Afterwards their flowers bloom and glow. This delightful display makes it very popular among Trainers.*

**DexID**:: 0829
**Name**:: Gossifleur
**Type**:: Grass
**Abilities**:: [[SRD-Cotton Down|Cotton Down]] / [[SRD-Regenerator|Regenerator]] ([[SRD-Effect Spore|Effect Spore]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 4.9lbs / 2.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Eldegoss]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Gossifleur.md"
flatten moves as T
where file.path = this.file.path
```
