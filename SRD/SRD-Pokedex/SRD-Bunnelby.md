---
Ability1: Pickup
Ability2: Cheek Pouch
BookSprite: SRD-bunnelby-BookSprite.png
BoxSprite: SRD-bunnelby-BoxSprite.png
DexCategory: Digging Pokemon
DexDescription: It uses its ears as shovels, digging holes strengthens them so much
  that they can sever thick roots easily. They reproduce quickly and a handful of
  them can ravage a field of vegetables in just a few hours.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Diggersby]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Huge Power
HomeSprite: SRD-bunnelby-HomeSprite.png
Image: bunnelby.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Agility|Agility]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Double Slap|Double Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Amateur
  - '[[SRD-Double Kick|Double Kick]]'
- - Amateur
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bounce|Bounce]]'
- - Ace
  - '[[SRD-Super Fang|Super Fang]]'
- - Ace
  - '[[SRD-Facade|Facade]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Pro
  - '[[SRD-Rollout|Rollout]]'
- - Pro
  - '[[SRD-Last Resort|Last Resort]]'
Number: 659
ShuffleToken: SRD-bunnelby-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 5.0
  Pounds: 11.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-bunnelby-BookSprite.png|wsmall]]
> ![[SRD-bunnelby-HomeSprite.png]]
> ![[SRD-bunnelby-BoxSprite.png|htiny]]
> ![[SRD-bunnelby-ShuffleToken.png|wsmall]]


*Digging Pokemon*
*It uses its ears as shovels, digging holes strengthens them so much that they can sever thick roots easily. They reproduce quickly and a handful of them can ravage a field of vegetables in just a few hours.*

**DexID**:: 0659
**Name**:: Bunnelby
**Type**:: Normal
**Abilities**:: [[SRD-Pickup|Pickup]] / [[SRD-Cheek Pouch|Cheek Pouch]] ([[SRD-Huge Power|Huge Power]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 11.0lbs / 5.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Diggersby]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Bunnelby.md"
flatten moves as T
where file.path = this.file.path
```
