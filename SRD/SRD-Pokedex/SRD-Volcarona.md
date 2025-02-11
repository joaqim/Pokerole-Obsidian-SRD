---
Ability1: Flame Body
Ability2: ''
BookSprite: SRD-volcarona-BookSprite.png
BoxSprite: SRD-volcarona-BoxSprite.png
DexCategory: Sun Pokemon
DexDescription: A sea of fire engulfs the surroundings of its battles, since it uses
  six wings to scatter blazing scales. There are stories of how its fire saved villages
  during winter and how it shone like the sun over the mountains.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Larvesta]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Swarm
HomeSprite: SRD-volcarona-HomeSprite.png
Image: volcarona.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Ember|Ember]]'
- - Starter
  - '[[SRD-String Shot|String Shot]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - Beginner
  - '[[SRD-Gust|Gust]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fire Spin|Fire Spin]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rage Powder|Rage Powder]]'
- - Ace
  - '[[SRD-Quiver Dance|Quiver Dance]]'
- - Ace
  - '[[SRD-Amnesia|Amnesia]]'
- - Ace
  - '[[SRD-Fiery Dance|Fiery Dance]]'
- - Ace
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Ace
  - '[[SRD-Silver Wind|Silver Wind]]'
- - Ace
  - '[[SRD-Heat Wave|Heat Wave]]'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Thrash|Thrash]]'
- - Pro
  - '[[SRD-Hurricane|Hurricane]]'
- - Pro
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - Pro
  - '[[SRD-Tailwind|Tailwind]]'
- - Pro
  - '[[SRD-Morning Sun|Morning Sun]]'
- - Pro
  - '[[SRD-Magnet Rise|Magnet Rise]]'
Number: 637
ShuffleToken: SRD-volcarona-ShuffleToken.png
Type1: Bug
Type2: Fire
Weight:
  Kilograms: 46.0
  Pounds: 101.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-volcarona-BookSprite.png|wsmall]]
> ![[SRD-volcarona-HomeSprite.png]]
> ![[SRD-volcarona-BoxSprite.png|htiny]]
> ![[SRD-volcarona-ShuffleToken.png|wsmall]]


*Sun Pokemon*
*A sea of fire engulfs the surroundings of its battles, since it uses six wings to scatter blazing scales. There are stories of how its fire saved villages during winter and how it shone like the sun over the mountains.*

**DexID**:: 0637
**Name**:: Volcarona
**Type**:: Bug / Fire
**Abilities**:: [[SRD-Flame Body|Flame Body]] ([[SRD-Swarm|Swarm]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'2" / 1.6m
**Weight**: 101.4lbs / 46.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Larvesta]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Volcarona.md"
flatten moves as T
where file.path = this.file.path
```
