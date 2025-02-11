---
Ability1: Stench
Ability2: Sticky Hold
BookSprite: SRD-muk-BookSprite.png
BoxSprite: SRD-muk-BoxSprite.png
DexCategory: Sludge Pokemon
DexDescription: It gathers on polluted areas to eat filth. Its body is made of a powerful
  poison that kills any plant. Touching it can cause a fever that will require bed
  rest. A good diet may reduce Muk's toxicity.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Grimer]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Poison Touch
HomeSprite: SRD-muk-HomeSprite.png
Image: muk.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Poison Gas|Poison Gas]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Harden|Harden]]'
- - Beginner
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Beginner
  - '[[SRD-Disable|Disable]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Venom Drench|Venom Drench]]'
- - Amateur
  - '[[SRD-Sludge|Sludge]]'
- - Amateur
  - '[[SRD-Minimize|Minimize]]'
- - Amateur
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - Amateur
  - '[[SRD-Sludge Bomb|Sludge Bomb]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sludge Wave|Sludge Wave]]'
- - Ace
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Ace
  - '[[SRD-Gunk Shot|Gunk Shot]]'
- - Ace
  - '[[SRD-Belch|Belch]]'
- - Ace
  - '[[SRD-Memento|Memento]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Pro
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
Number: 89
ShuffleToken: SRD-muk-ShuffleToken.png
Type1: Poison
Type2: ''
Weight:
  Kilograms: 30.0
  Pounds: 66.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-muk-BookSprite.png|wsmall]]
> ![[SRD-muk-HomeSprite.png]]
> ![[SRD-muk-BoxSprite.png|htiny]]
> ![[SRD-muk-ShuffleToken.png|wsmall]]


*Sludge Pokemon*
*It gathers on polluted areas to eat filth. Its body is made of a powerful poison that kills any plant. Touching it can cause a fever that will require bed rest. A good diet may reduce Muk's toxicity.*

**DexID**:: 0089
**Name**:: Muk
**Type**:: Poison
**Abilities**:: [[SRD-Stench|Stench]] / [[SRD-Sticky Hold|Sticky Hold]] ([[SRD-Poison Touch|Poison Touch]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'9" / 1.2m
**Weight**: 66.1lbs / 30.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Grimer]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Muk.md"
flatten moves as T
where file.path = this.file.path
```
