---
Ability1: Rock Head
Ability2: Lightning Rod
BookSprite: SRD-cubone-BookSprite.png
BoxSprite: SRD-cubone-BoxSprite.png
DexCategory: Lonely Pokemon
DexDescription: Cubone wears a skull helmet it never removes. It is said to be from
  its mother or someone dear to it. Lives in the mountains where it cries at night
  due to the sadness it feels. It is distrustful of humans.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Marowak]]'
  Speed: Slow
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Marowak (Alolan Form)]]'
  Region: Alola
  Speed: Slow
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Battle Armor
HomeSprite: SRD-cubone-HomeSprite.png
Image: cubone.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bone Club|Bone Club]]'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Bonemerang|Bonemerang]]'
- - Amateur
  - '[[SRD-Rage|Rage]]'
- - Amateur
  - '[[SRD-False Swipe|False Swipe]]'
- - Amateur
  - '[[SRD-Endeavor|Endeavor]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bone Rush|Bone Rush]]'
- - Ace
  - '[[SRD-Stomping Tantrum|Stomping Tantrum]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Retaliate|Retaliate]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Double Kick|Double Kick]]'
- - Pro
  - '[[SRD-Detect|Detect]]'
Number: 104
ShuffleToken: SRD-cubone-ShuffleToken.png
Type1: Ground
Type2: ''
Weight:
  Kilograms: 6.5
  Pounds: 14.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cubone-BookSprite.png|wsmall]]
> ![[SRD-cubone-HomeSprite.png]]
> ![[SRD-cubone-BoxSprite.png|htiny]]
> ![[SRD-cubone-ShuffleToken.png|wsmall]]


*Lonely Pokemon*
*Cubone wears a skull helmet it never removes. It is said to be from its mother or someone dear to it. Lives in the mountains where it cries at night due to the sadness it feels. It is distrustful of humans.*

**DexID**:: 0104
**Name**:: Cubone
**Type**:: Ground
**Abilities**:: [[SRD-Rock Head|Rock Head]] / [[SRD-Lightning Rod|Lightning Rod]] ([[SRD-Battle Armor|Battle Armor]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 14.3lbs / 6.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon                       | Kind   | Speed   | Region   |
|:----------|:------------------------------|:-------|:--------|:---------|
| To        | [[SRD-Marowak]]               | Level  | Slow    |          |
| To        | [[SRD-Marowak (Alolan Form)]] | Level  | Slow    | Alola    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Cubone.md"
flatten moves as T
where file.path = this.file.path
```
