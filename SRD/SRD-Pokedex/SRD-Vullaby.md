---
Ability1: Big Pecks
Ability2: Overcoat
BookSprite: SRD-vullaby-BookSprite.png
BoxSprite: SRD-vullaby-BoxSprite.png
DexCategory: Diapered Pokemon
DexDescription: This is a female-only species. They stay with their Mandibuzz mothers
  from birth until they can finally fly. They feed on the carrion meat the mothers
  bring back to the nest and keep the bones to make accessories.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Mandibuzz]]'
  Speed: Medium
GenderType: F
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Weak Armor
HomeSprite: SRD-vullaby-HomeSprite.png
Image: vullaby.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Gust|Gust]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Beginner
  - '[[SRD-Pluck|Pluck]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Amateur
  - '[[SRD-Flatter|Flatter]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Punishment|Punishment]]'
- - Amateur
  - '[[SRD-Defog|Defog]]'
- - Amateur
  - '[[SRD-Tailwind|Tailwind]]'
- - Amateur
  - '[[SRD-Air Slash|Air Slash]]'
- - Amateur
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Embargo|Embargo]]'
- - Ace
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Ace
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Ace
  - '[[SRD-Mirror Move|Mirror Move]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Scary Face|Scary Face]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
Number: 629
ShuffleToken: SRD-vullaby-ShuffleToken.png
Type1: Dark
Type2: Flying
Weight:
  Kilograms: 9.0
  Pounds: 19.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-vullaby-BookSprite.png|wsmall]]
> ![[SRD-vullaby-HomeSprite.png]]
> ![[SRD-vullaby-BoxSprite.png|htiny]]
> ![[SRD-vullaby-ShuffleToken.png|wsmall]]


*Diapered Pokemon*
*This is a female-only species. They stay with their Mandibuzz mothers from birth until they can finally fly. They feed on the carrion meat the mothers bring back to the nest and keep the bones to make accessories.*

**DexID**:: 0629
**Name**:: Vullaby
**Type**:: Dark / Flying
**Abilities**:: [[SRD-Big Pecks|Big Pecks]] / [[SRD-Overcoat|Overcoat]] ([[SRD-Weak Armor|Weak Armor]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 1'6" / 0.5m
**Weight**: 19.8lbs / 9.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Mandibuzz]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Vullaby.md"
flatten moves as T
where file.path = this.file.path
```
