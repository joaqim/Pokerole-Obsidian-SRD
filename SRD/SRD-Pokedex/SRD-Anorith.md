---
Ability1: Battle Armor
Ability2: ''
BookSprite: SRD-anorith-BookSprite.png
BoxSprite: SRD-anorith-BoxSprite.png
DexCategory: Old Shrimp Pokemon
DexDescription: This ancient Pokemon is thought to be the common ancestor of many
  modern Bug Pokemon. The fossils show it lived in big schools and it preferred warm
  waters. Anoriths used their claws to catch small prey.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Armaldo]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Swift Swim
HomeSprite: SRD-anorith-HomeSprite.png
Image: anorith.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Harden|Harden]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Mud Sport|Mud Sport]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Water Gun|Water Gun]]'
- - Amateur
  - '[[SRD-Smack Down|Smack Down]]'
- - Amateur
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Brine|Brine]]'
- - Ace
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Ace
  - '[[SRD-Crush Claw|Crush Claw]]'
- - Ace
  - '[[SRD-X-Scissor|X-Scissor]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Knock Off|Knock Off]]'
- - Pro
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Pro
  - '[[SRD-Aqua Jet|Aqua Jet]]'
Number: 347
ShuffleToken: SRD-anorith-ShuffleToken.png
Type1: Rock
Type2: Bug
Weight:
  Kilograms: 12.5
  Pounds: 27.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-anorith-BookSprite.png|wsmall]]
> ![[SRD-anorith-HomeSprite.png]]
> ![[SRD-anorith-BoxSprite.png|htiny]]
> ![[SRD-anorith-ShuffleToken.png|wsmall]]


*Old Shrimp Pokemon*
*This ancient Pokemon is thought to be the common ancestor of many modern Bug Pokemon. The fossils show it lived in big schools and it preferred warm waters. Anoriths used their claws to catch small prey.*

**DexID**:: 0347
**Name**:: Anorith
**Type**:: Rock / Bug
**Abilities**:: [[SRD-Battle Armor|Battle Armor]] ([[SRD-Swift Swim|Swift Swim]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'3" / 0.7m
**Weight**: 27.6lbs / 12.5kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Armaldo]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Anorith.md"
flatten moves as T
where file.path = this.file.path
```
