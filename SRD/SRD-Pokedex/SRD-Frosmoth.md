---
Ability1: Shield Dust
Ability2: ''
BookSprite: SRD-frosmoth-BookSprite.png
BoxSprite: SRD-frosmoth-BoxSprite.png
DexCategory: Frost Moth Pokemon
DexDescription: It shows no mercy to any who desecrates its snowfields and mountains.
  It will fly around on its icy wings, causing a blizzard to chase offenders away.
  It is very regal and soft-mannered otherwise
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Stat
  Pokemon: '[[SRD-Snom]]'
  Stat: Happiness
  Value: 5
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Ice Scales
HomeSprite: SRD-frosmoth-HomeSprite.png
Image: frosmoth.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Powder Snow|Powder Snow]]'
- - Starter
  - '[[SRD-Struggle Bug|Struggle Bug]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Beginner
  - '[[SRD-Helping Hand|Helping Hand]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Attract|Attract]]'
- - Amateur
  - '[[SRD-Stun Spore|Stun Spore]]'
- - Amateur
  - '[[SRD-Infestation|Infestation]]'
- - Amateur
  - '[[SRD-Mist|Mist]]'
- - Amateur
  - '[[SRD-Defog|Defog]]'
- - Amateur
  - '[[SRD-Feather Dance|Feather Dance]]'
- - Amateur
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Amateur
  - '[[SRD-Hail|Hail]]'
- - Amateur
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Amateur
  - '[[SRD-Aurora Veil|Aurora Veil]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[SRD-Tailwind|Tailwind]]'
- - Ace
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Ace
  - '[[SRD-Quiver Dance|Quiver Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dazzling Gleam|Dazzling Gleam]]'
- - Pro
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - Pro
  - '[[SRD-Hurricane|Hurricane]]'
Number: 873
ShuffleToken: SRD-frosmoth-ShuffleToken.png
Type1: Ice
Type2: Bug
Weight:
  Kilograms: 42.0
  Pounds: 92.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-frosmoth-BookSprite.png|wsmall]]
> ![[SRD-frosmoth-HomeSprite.png]]
> ![[SRD-frosmoth-BoxSprite.png|htiny]]
> ![[SRD-frosmoth-ShuffleToken.png|wsmall]]


*Frost Moth Pokemon*
*It shows no mercy to any who desecrates its snowfields and mountains. It will fly around on its icy wings, causing a blizzard to chase offenders away. It is very regal and soft-mannered otherwise*

**DexID**:: 0873
**Name**:: Frosmoth
**Type**:: Ice / Bug
**Abilities**:: [[SRD-Shield Dust|Shield Dust]] ([[SRD-Ice Scales|Ice Scales]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'3" / 1.3m
**Weight**: 92.6lbs / 42.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon      | Kind   | Stat      |   Value |
|:----------|:-------------|:-------|:----------|--------:|
| From      | [[SRD-Snom]] | Stat   | Happiness |       5 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Frosmoth.md"
flatten moves as T
where file.path = this.file.path
```
