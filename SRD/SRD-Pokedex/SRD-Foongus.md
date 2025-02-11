---
Ability1: Effect Spore
Ability2: ''
BookSprite: SRD-foongus-BookSprite.png
BoxSprite: SRD-foongus-BoxSprite.png
DexCategory: Mushroom Pokemon
DexDescription: The top of fungus takes a pattern that resembles a predator to protect
  itself. In recent times this pattern has started to look like a Pokeball. It releases
  toxic spores in the air that help it move around safely.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Amoonguss]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: Regenerator
HomeSprite: SRD-foongus-HomeSprite.png
Image: foongus.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - Starter
  - '[[SRD-Growth|Growth]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - Beginner
  - '[[SRD-Bide|Bide]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Ingrain|Ingrain]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[SRD-Synthesis|Synthesis]]'
- - Amateur
  - '[[SRD-Toxic|Toxic]]'
- - Amateur
  - '[[SRD-Clear Smog|Clear Smog]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Ace
  - '[[SRD-Solar Beam|Solar Beam]]'
- - Ace
  - '[[SRD-Rage Powder|Rage Powder]]'
- - Ace
  - '[[SRD-Spore|Spore]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Pro
  - '[[SRD-Body Slam|Body Slam]]'
- - Pro
  - '[[SRD-Gastro Acid|Gastro Acid]]'
Number: 590
ShuffleToken: SRD-foongus-ShuffleToken.png
Type1: Grass
Type2: Poison
Weight:
  Kilograms: 1.0
  Pounds: 2.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-foongus-BookSprite.png|wsmall]]
> ![[SRD-foongus-HomeSprite.png]]
> ![[SRD-foongus-BoxSprite.png|htiny]]
> ![[SRD-foongus-ShuffleToken.png|wsmall]]


*Mushroom Pokemon*
*The top of fungus takes a pattern that resembles a predator to protect itself. In recent times this pattern has started to look like a Pokeball. It releases toxic spores in the air that help it move around safely.*

**DexID**:: 0590
**Name**:: Foongus
**Type**:: Grass / Poison
**Abilities**:: [[SRD-Effect Spore|Effect Spore]] ([[SRD-Regenerator|Regenerator]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 0'7" / 0.2m
**Weight**: 2.2lbs / 1.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Amoonguss]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Foongus.md"
flatten moves as T
where file.path = this.file.path
```
