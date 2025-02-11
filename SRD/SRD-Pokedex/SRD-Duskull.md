---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-duskull-BookSprite.png
BoxSprite: SRD-duskull-BoxSprite.png
DexCategory: Requiem Pokemon
DexDescription: They wander at night. They can make themselves invisible and they
  follow travelers all night until dawn breaks. It loves the crying of little children,
  they can be seen scaring kids who misbehaved during the day.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Dusclops]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Frisk
HomeSprite: SRD-duskull-HomeSprite.png
Image: duskull.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Night Shade|Night Shade]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Disable|Disable]]'
- - Beginner
  - '[[SRD-Foresight|Foresight]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Astonish|Astonish]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - Amateur
  - '[[SRD-Hex|Hex]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Mean Look|Mean Look]]'
- - Ace
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Ace
  - '[[SRD-Payback|Payback]]'
- - Ace
  - '[[SRD-Future Sight|Future Sight]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Pro
  - '[[SRD-Spite|Spite]]'
- - Pro
  - '[[SRD-Wonder Room|Wonder Room]]'
Number: 355
ShuffleToken: SRD-duskull-ShuffleToken.png
Type1: Ghost
Type2: ''
Weight:
  Kilograms: 15.0
  Pounds: 33.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-duskull-BookSprite.png|wsmall]]
> ![[SRD-duskull-HomeSprite.png]]
> ![[SRD-duskull-BoxSprite.png|htiny]]
> ![[SRD-duskull-ShuffleToken.png|wsmall]]


*Requiem Pokemon*
*They wander at night. They can make themselves invisible and they follow travelers all night until dawn breaks. It loves the crying of little children, they can be seen scaring kids who misbehaved during the day.*

**DexID**:: 0355
**Name**:: Duskull
**Type**:: Ghost
**Abilities**:: [[SRD-Levitate|Levitate]] ([[SRD-Frisk|Frisk]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'6" / 0.8m
**Weight**: 33.1lbs / 15.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Dusclops]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Duskull.md"
flatten moves as T
where file.path = this.file.path
```
