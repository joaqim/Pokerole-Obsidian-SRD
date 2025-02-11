---
Ability1: Drizzle
Ability2: ''
BookSprite: SRD-kyogre-BookSprite.png
BoxSprite: SRD-kyogre-BoxSprite.png
DexCategory: No Data
DexDescription: Kyogre is named in mythology as the God that expanded the seas and
  oceans with torrential waters and huge tidal waves. It is the mortal enemy of Groudon.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Kyogre (Primal Form)]]'
GenderType: N
Height:
  Feet: 14.8
  Meters: 4.5
HiddenAbility: ''
HomeSprite: SRD-kyogre-HomeSprite.png
Image: kyogre.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Master
  - '[[SRD-Scary Face|Scary Face]]'
- - Master
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Master
  - '[[SRD-Ice Beam|Ice Beam]]'
- - Master
  - '[[SRD-Origin Pulse|Origin Pulse]]'
- - Master
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Master
  - '[[SRD-Muddy Water|Muddy Water]]'
- - Master
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - Master
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Master
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Master
  - '[[SRD-Water Spout|Water Spout]]'
- - Master
  - '[[SRD-Strength|Strength]]'
- - Master
  - '[[SRD-Dive|Dive]]'
- - Master
  - '[[SRD-Whirlpool|Whirlpool]]'
- - Master
  - '[[SRD-Psych Up|Psych Up]]'
- - Master
  - '[[SRD-Mist|Mist]]'
- - Master
  - '[[SRD-Splishy Splash|Splishy Splash]]'
- - Master
  - '[[SRD-Steam Eruption|Steam Eruption]]'
- - Master
  - '[[SRD-Defog|Defog]]'
- - Master
  - '[[SRD-Telekinesis|Telekinesis]]'
- - Master
  - '[[SRD-Blizzard|Blizzard]]'
- - Master
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Master
  - '[[SRD-Snatch|Snatch]]'
Number: 382
ShuffleToken: SRD-kyogre-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 352.0
  Pounds: 776.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-kyogre-BookSprite.png|wsmall]]
> ![[SRD-kyogre-HomeSprite.png]]
> ![[SRD-kyogre-BoxSprite.png|htiny]]
> ![[SRD-kyogre-ShuffleToken.png|wsmall]]


*No Data*
*Kyogre is named in mythology as the God that expanded the seas and oceans with torrential waters and huge tidal waves. It is the mortal enemy of Groudon.*

**DexID**:: 0382
**Name**:: Kyogre
**Type**:: Water
**Abilities**:: [[SRD-Drizzle|Drizzle]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::8)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::7)/(MaxInsight::7)     |

**Height**: 14'8" / 4.5m
**Weight**: 776.0lbs / 352.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon                      | Kind   |
|:----------|:-----------------------------|:-------|
| To        | [[SRD-Kyogre (Primal Form)]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Kyogre.md"
flatten moves as T
where file.path = this.file.path
```
