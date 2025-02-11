---
Ability1: Chlorophyll
Ability2: ''
BookSprite: SRD-exeggcute-BookSprite.png
BoxSprite: SRD-exeggcute-BoxSprite.png
DexCategory: Egg Pokemon
DexDescription: Even though it appears to be eggs of some sort, it is related more
  to a seed. It gathers in packs of six that have a mental link with each other. Each
  one of them has a different personality.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Leaf Stone
  Kind: Stone
  Pokemon: '[[SRD-Exeggutor]]'
- Evolves: To
  Item: Leaf Stone
  Kind: Stone
  Pokemon: '[[SRD-Exeggutor (Alolan Form)]]'
  Region: Alola
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Harvest
HomeSprite: SRD-exeggcute-HomeSprite.png
Image: exeggcute.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Barrage|Barrage]]'
- - Starter
  - '[[SRD-Uproar|Uproar]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Beginner
  - '[[SRD-Reflect|Reflect]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - Amateur
  - '[[SRD-Stun Spore|Stun Spore]]'
- - Amateur
  - '[[SRD-Poison Powder|Poison Powder]]'
- - Amateur
  - '[[SRD-Sleep Powder|Sleep Powder]]'
- - Amateur
  - '[[SRD-Confusion|Confusion]]'
- - Amateur
  - '[[SRD-Worry Seed|Worry Seed]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Ace
  - '[[SRD-Solar Beam|Solar Beam]]'
- - Ace
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Ace
  - '[[SRD-Bestow|Bestow]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Nightmare|Nightmare]]'
- - Pro
  - '[[SRD-Ingrain|Ingrain]]'
- - Pro
  - '[[SRD-Curse|Curse]]'
Number: 102
ShuffleToken: SRD-exeggcute-ShuffleToken.png
Type1: Grass
Type2: Psychic
Weight:
  Kilograms: 2.5
  Pounds: 5.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-exeggcute-BookSprite.png|wsmall]]
> ![[SRD-exeggcute-HomeSprite.png]]
> ![[SRD-exeggcute-BoxSprite.png|htiny]]
> ![[SRD-exeggcute-ShuffleToken.png|wsmall]]


*Egg Pokemon*
*Even though it appears to be eggs of some sort, it is related more to a seed. It gathers in packs of six that have a mental link with each other. Each one of them has a different personality.*

**DexID**:: 0102
**Name**:: Exeggcute
**Type**:: Grass / Psychic
**Abilities**:: [[SRD-Chlorophyll|Chlorophyll]] ([[SRD-Harvest|Harvest]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 5.5lbs / 2.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon                         | Kind   | Item       | Region   |
|:----------|:--------------------------------|:-------|:-----------|:---------|
| To        | [[SRD-Exeggutor]]               | Stone  | Leaf Stone |          |
| To        | [[SRD-Exeggutor (Alolan Form)]] | Stone  | Leaf Stone | Alola    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Exeggcute.md"
flatten moves as T
where file.path = this.file.path
```
