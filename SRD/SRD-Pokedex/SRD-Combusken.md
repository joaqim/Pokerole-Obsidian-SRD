---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-combusken-BookSprite.png
BoxSprite: SRD-combusken-BoxSprite.png
DexCategory: Young Fowl Pokemon
DexDescription: Once Torchic toughened up its legs and thighs, they like to run and
  love to kick. They have an offensive instinct to keep attacking no matter what.
  They sqwak loudly every morning when they start to train.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Torchic]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Blaziken]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Speed Boost
HomeSprite: SRD-combusken-HomeSprite.png
Image: combusken.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Double Kick|Double Kick]]'
- - Beginner
  - '[[SRD-Peck|Peck]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Amateur
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Amateur
  - '[[SRD-Bulk Up|Bulk Up]]'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Mirror Move|Mirror Move]]'
- - Ace
  - '[[SRD-Sky Uppercut|Sky Uppercut]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Counter|Counter]]'
- - Pro
  - '[[SRD-Feather Dance|Feather Dance]]'
- - Pro
  - '[[SRD-Fire Pledge|Fire Pledge]]'
Number: 256
ShuffleToken: SRD-combusken-ShuffleToken.png
Type1: Fire
Type2: Fighting
Weight:
  Kilograms: 19.5
  Pounds: 43.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-combusken-BookSprite.png|wsmall]]
> ![[SRD-combusken-HomeSprite.png]]
> ![[SRD-combusken-BoxSprite.png|htiny]]
> ![[SRD-combusken-ShuffleToken.png|wsmall]]


*Young Fowl Pokemon*
*Once Torchic toughened up its legs and thighs, they like to run and love to kick. They have an offensive instinct to keep attacking no matter what. They sqwak loudly every morning when they start to train.*

**DexID**:: 0256
**Name**:: Combusken
**Type**:: Fire / Fighting
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Speed Boost|Speed Boost]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'0" / 0.9m
**Weight**: 43.0lbs / 19.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Torchic]]  | Level  | Medium  |
| To        | [[SRD-Blaziken]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Combusken.md"
flatten moves as T
where file.path = this.file.path
```
