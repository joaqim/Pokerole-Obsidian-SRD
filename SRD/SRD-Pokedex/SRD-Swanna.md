---
Ability1: Keen Eye
Ability2: Big Pecks
BookSprite: SRD-swanna-BookSprite.png
BoxSprite: SRD-swanna-BoxSprite.png
DexCategory: White Bird Pokemon
DexDescription: Swanna come out to dance at dusk. The one dancing in the middle is
  the leader of the flock. Despite their elegant and frail appearance, they can flap
  their wings strongly and fly for thousands of miles.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Ducklett]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Hydration
HomeSprite: SRD-swanna-HomeSprite.png
Image: swanna.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - Starter
  - '[[SRD-Water Sport|Water Sport]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Defog|Defog]]'
- - Beginner
  - '[[SRD-Wing Attack|Wing Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Feather Dance|Feather Dance]]'
- - Amateur
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Amateur
  - '[[SRD-Air Slash|Air Slash]]'
- - Amateur
  - '[[SRD-Roost|Roost]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Ace
  - '[[SRD-Tailwind|Tailwind]]'
- - Ace
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Ace
  - '[[SRD-Hurricane|Hurricane]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Pro
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Pro
  - '[[SRD-Mirror Move|Mirror Move]]'
Number: 581
ShuffleToken: SRD-swanna-ShuffleToken.png
Type1: Water
Type2: Flying
Weight:
  Kilograms: 24.2
  Pounds: 53.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-swanna-BookSprite.png|wsmall]]
> ![[SRD-swanna-HomeSprite.png]]
> ![[SRD-swanna-BoxSprite.png|htiny]]
> ![[SRD-swanna-ShuffleToken.png|wsmall]]


*White Bird Pokemon*
*Swanna come out to dance at dusk. The one dancing in the middle is the leader of the flock. Despite their elegant and frail appearance, they can flap their wings strongly and fly for thousands of miles.*

**DexID**:: 0581
**Name**:: Swanna
**Type**:: Water / Flying
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Big Pecks|Big Pecks]] ([[SRD-Hydration|Hydration]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'3" / 1.3m
**Weight**: 53.4lbs / 24.2kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Ducklett]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Swanna.md"
flatten moves as T
where file.path = this.file.path
```
