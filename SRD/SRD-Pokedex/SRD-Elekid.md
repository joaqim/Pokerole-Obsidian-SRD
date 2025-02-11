---
Ability1: Static
Ability2: ''
BookSprite: SRD-elekid-BookSprite.png
BoxSprite: SRD-elekid-BoxSprite.png
DexCategory: Electric Pokemon
DexDescription: They can be found following thunder storms. Elekids rotate their arms
  constantly to charge electricity. Beware, there is an electric current between their
  horns that may zap you if you touch them.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Electabuzz]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Vital Spirit
HomeSprite: SRD-elekid-HomeSprite.png
Image: elekid.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Beginner
  - '[[SRD-Low Kick|Low Kick]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Shock Wave|Shock Wave]]'
- - Amateur
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Amateur
  - '[[SRD-Electro Ball|Electro Ball]]'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Thunderbolt|Thunderbolt]]'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Thunder|Thunder]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Meditate|Meditate]]'
- - Pro
  - '[[SRD-Karate Chop|Karate Chop]]'
- - Pro
  - '[[SRD-Uproar|Uproar]]'
Number: 239
ShuffleToken: SRD-elekid-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 23.5
  Pounds: 51.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-elekid-BookSprite.png|wsmall]]
> ![[SRD-elekid-HomeSprite.png]]
> ![[SRD-elekid-BoxSprite.png|htiny]]
> ![[SRD-elekid-ShuffleToken.png|wsmall]]


*Electric Pokemon*
*They can be found following thunder storms. Elekids rotate their arms constantly to charge electricity. Beware, there is an electric current between their horns that may zap you if you touch them.*

**DexID**:: 0239
**Name**:: Elekid
**Type**:: Electric
**Abilities**:: [[SRD-Static|Static]] ([[SRD-Vital Spirit|Vital Spirit]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 51.8lbs / 23.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| To        | [[SRD-Electabuzz]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Elekid.md"
flatten moves as T
where file.path = this.file.path
```
