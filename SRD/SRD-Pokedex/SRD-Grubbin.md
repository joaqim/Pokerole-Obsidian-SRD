---
Ability1: Swarm
Ability2: ''
BookSprite: SRD-grubbin-BookSprite.png
BoxSprite: SRD-grubbin-BoxSprite.png
DexCategory: Larva Pokemon
DexDescription: They tend to gather anywhere Electric Pokemon live to protect themselves
  from bird Pokemon who may prey on them. When they are ready to evolve they bury
  themselves underground.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Charjabug]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: ''
HomeSprite: SRD-grubbin-HomeSprite.png
Image: grubbin.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Vice Grip|Vice Grip]]'
- - Starter
  - '[[SRD-String Shot|String Shot]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Bug Bite|Bug Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Acrobatics|Acrobatics]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-X-Scissor|X-Scissor]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Electroweb|Electroweb]]'
- - Pro
  - '[[SRD-Harden|Harden]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
Number: 736
ShuffleToken: SRD-grubbin-ShuffleToken.png
Type1: Bug
Type2: ''
Weight:
  Kilograms: 4.4
  Pounds: 9.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-grubbin-BookSprite.png|wsmall]]
> ![[SRD-grubbin-HomeSprite.png]]
> ![[SRD-grubbin-BoxSprite.png|htiny]]
> ![[SRD-grubbin-ShuffleToken.png|wsmall]]


*Larva Pokemon*
*They tend to gather anywhere Electric Pokemon live to protect themselves from bird Pokemon who may prey on them. When they are ready to evolve they bury themselves underground.*

**DexID**:: 0736
**Name**:: Grubbin
**Type**:: Bug
**Abilities**:: [[SRD-Swarm|Swarm]]
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 9.7lbs / 4.4kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Charjabug]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Grubbin.md"
flatten moves as T
where file.path = this.file.path
```
