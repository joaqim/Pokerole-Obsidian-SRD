---
Ability1: Sturdy
Ability2: Rock Head
BookSprite: SRD-aggron-BookSprite.png
BoxSprite: SRD-aggron-BoxSprite.png
DexCategory: Iron Armor Pokemon
DexDescription: Aggron claims ownership of entire mountains, mercilessly beating up
  anything that crosses their path. Aggrons are violent and patrol their territory
  at all times, but also plant trees, stop fires and protect nature.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Lairon]]'
  Speed: Slow
- Evolves: To
  Item: Aggronite
  Kind: Mega
  Pokemon: '[[SRD-Aggron (Mega Form)]]'
GenderType: ''
Height:
  Feet: 6.9
  Meters: 2.1
HiddenAbility: Heavy Metal
HomeSprite: SRD-aggron-HomeSprite.png
Image: aggron.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Harden|Harden]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - Beginner
  - '[[SRD-Metal Claw|Metal Claw]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rock Tomb|Rock Tomb]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Iron Head|Iron Head]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Iron Tail|Iron Tail]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Autotomize|Autotomize]]'
- - Ace
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Metal Burst|Metal Burst]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Head Smash|Head Smash]]'
- - Pro
  - '[[SRD-Dragon Rush|Dragon Rush]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
Number: 306
ShuffleToken: SRD-aggron-ShuffleToken.png
Type1: Steel
Type2: Rock
Weight:
  Kilograms: 360.0
  Pounds: 793.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-aggron-BookSprite.png|wsmall]]
> ![[SRD-aggron-HomeSprite.png]]
> ![[SRD-aggron-BoxSprite.png|htiny]]
> ![[SRD-aggron-ShuffleToken.png|wsmall]]


*Iron Armor Pokemon*
*Aggron claims ownership of entire mountains, mercilessly beating up anything that crosses their path. Aggrons are violent and patrol their territory at all times, but also plant trees, stop fires and protect nature.*

**DexID**:: 0306
**Name**:: Aggron
**Type**:: Steel / Rock
**Abilities**:: [[SRD-Sturdy|Sturdy]] / [[SRD-Rock Head|Rock Head]] ([[SRD-Heavy Metal|Heavy Metal]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::4)/(MaxVitality::9)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 6'9" / 2.1m
**Weight**: 793.7lbs / 360.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon                    | Kind   | Speed   | Item      |
|:----------|:---------------------------|:-------|:--------|:----------|
| From      | [[SRD-Lairon]]             | Level  | Slow    |           |
| To        | [[SRD-Aggron (Mega Form)]] | Mega   |         | Aggronite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Aggron.md"
flatten moves as T
where file.path = this.file.path
```
