---
Ability1: Magma Armor
Ability2: Solid Rock
BookSprite: SRD-camerupt-BookSprite.png
BoxSprite: SRD-camerupt-BoxSprite.png
DexCategory: Eruption Pokemon
DexDescription: "Sometimes the humps on their back make an eruption when they get\
  \ really angry, otherwise they\u2019d only erupt every 10 years. Camerupts live\
  \ inside the craters of volcanoes. They are indifferent to humans."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Numel]]'
  Speed: Medium
- Evolves: To
  Item: Cameruptite
  Kind: Mega
  Pokemon: '[[SRD-Camerupt (Mega Form)]]'
GenderType: ''
Height:
  Feet: 6.2
  Meters: 1.9
HiddenAbility: Anger Point
HomeSprite: SRD-camerupt-HomeSprite.png
Image: camerupt.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Magnitude|Magnitude]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Lava Plume|Lava Plume]]'
- - Amateur
  - '[[SRD-Earth Power|Earth Power]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Yawn|Yawn]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Eruption|Eruption]]'
- - Ace
  - '[[SRD-Fissure|Fissure]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
Number: 323
ShuffleToken: SRD-camerupt-ShuffleToken.png
Type1: Fire
Type2: Ground
Weight:
  Kilograms: 220.0
  Pounds: 485.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-camerupt-BookSprite.png|wsmall]]
> ![[SRD-camerupt-HomeSprite.png]]
> ![[SRD-camerupt-BoxSprite.png|htiny]]
> ![[SRD-camerupt-ShuffleToken.png|wsmall]]


*Eruption Pokemon*
*Sometimes the humps on their back make an eruption when they get really angry, otherwise they’d only erupt every 10 years. Camerupts live inside the craters of volcanoes. They are indifferent to humans.*

**DexID**:: 0323
**Name**:: Camerupt
**Type**:: Fire / Ground
**Abilities**:: [[SRD-Magma Armor|Magma Armor]] / [[SRD-Solid Rock|Solid Rock]] ([[SRD-Anger Point|Anger Point]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'2" / 1.9m
**Weight**: 485.0lbs / 220.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                      | Kind   | Speed   | Item        |
|:----------|:-----------------------------|:-------|:--------|:------------|
| From      | [[SRD-Numel]]                | Level  | Medium  |             |
| To        | [[SRD-Camerupt (Mega Form)]] | Mega   |         | Cameruptite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Camerupt.md"
flatten moves as T
where file.path = this.file.path
```
