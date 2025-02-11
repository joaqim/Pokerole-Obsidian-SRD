---
Ability1: Rivalry
Ability2: Unnerve
BookSprite: SRD-litleo-BookSprite.png
BoxSprite: SRD-litleo-BoxSprite.png
DexCategory: Lion Cub Pokemon
DexDescription: Quick on temper and to take on a fight. They use their mane to scorch
  their enemies. Some of them set off from their pride to live alone. Only those who
  develop a full mane get to lead their own pride.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Pyroar]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Moxie
HomeSprite: SRD-litleo-HomeSprite.png
Image: litleo.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Work Up|Work Up]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Noble Roar|Noble Roar]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Endeavor|Endeavor]]'
- - Amateur
  - '[[SRD-Echoed Voice|Echoed Voice]]'
- - Amateur
  - '[[SRD-Flamethrower|Flamethrower]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Ace
  - '[[SRD-Incinerate|Incinerate]]'
- - Ace
  - '[[SRD-Overheat|Overheat]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
- - Pro
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
Number: 667
ShuffleToken: SRD-litleo-ShuffleToken.png
Type1: Fire
Type2: Normal
Weight:
  Kilograms: 13.5
  Pounds: 29.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-litleo-BookSprite.png|wsmall]]
> ![[SRD-litleo-HomeSprite.png]]
> ![[SRD-litleo-BoxSprite.png|htiny]]
> ![[SRD-litleo-ShuffleToken.png|wsmall]]


*Lion Cub Pokemon*
*Quick on temper and to take on a fight. They use their mane to scorch their enemies. Some of them set off from their pride to live alone. Only those who develop a full mane get to lead their own pride.*

**DexID**:: 0667
**Name**:: Litleo
**Type**:: Fire / Normal
**Abilities**:: [[SRD-Rivalry|Rivalry]] / [[SRD-Unnerve|Unnerve]] ([[SRD-Moxie|Moxie]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 29.8lbs / 13.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| To        | [[SRD-Pyroar]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Litleo.md"
flatten moves as T
where file.path = this.file.path
```
