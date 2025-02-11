---
Ability1: Defiant
Ability2: ''
BookSprite: SRD-zapdos-galarian-form-BookSprite.png
BoxSprite: SRD-zapdos-galarian-form-BoxSprite.png
DexCategory: ''
DexDescription: ''
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: ''
HomeSprite: SRD-zapdos-galarian-form-HomeSprite.png
Image: zapdos-galarian-form.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Peck|Peck]]'
- - Master
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Master
  - '[[SRD-Rock Smash|Rock Smash]]'
- - Master
  - '[[SRD-Light Screen|Light Screen]]'
- - Master
  - '[[SRD-Pluck|Pluck]]'
- - Master
  - '[[SRD-Agility|Agility]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Brick Break|Brick Break]]'
- - Master
  - '[[SRD-Drill Peck|Drill Peck]]'
- - Master
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Master
  - '[[SRD-Thunderous Kick|Thunderous Kick]]'
- - Master
  - '[[SRD-Bulk Up|Bulk Up]]'
- - Master
  - '[[SRD-Counter|Counter]]'
- - Master
  - '[[SRD-Detect|Detect]]'
- - Master
  - '[[SRD-Close Combat|Close Combat]]'
- - Master
  - '[[SRD-Reversal|Reversal]]'
- - Master
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Master
  - '[[SRD-Stomping Tantrum|Stomping Tantrum]]'
- - Master
  - '[[SRD-Blaze Kick|Blaze Kick]]'
Number: 145
ShuffleToken: SRD-zapdos-galarian-form-ShuffleToken.png
Type1: Fighting
Type2: Flying
Weight:
  Kilograms: 58.2
  Pounds: 128.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-zapdos-galarian-form-BookSprite.png|wsmall]]
> ![[SRD-zapdos-galarian-form-HomeSprite.png]]
> ![[SRD-zapdos-galarian-form-BoxSprite.png|htiny]]
> ![[SRD-zapdos-galarian-form-ShuffleToken.png|wsmall]]


**
**

**DexID**:: 0145G
**Name**:: Zapdos (Galarian Form)
**Type**:: Fighting / Flying
**Abilities**:: [[SRD-Defiant|Defiant]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::5)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 5'2" / 1.6m
**Weight**: 128.3lbs / 58.2kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Zapdos (Galarian Form).md"
flatten moves as T
where file.path = this.file.path
```
