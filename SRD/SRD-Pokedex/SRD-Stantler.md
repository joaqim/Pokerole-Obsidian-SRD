---
Ability1: Intimidate
Ability2: Frisk
BookSprite: SRD-stantler-BookSprite.png
BoxSprite: SRD-stantler-BoxSprite.png
DexCategory: Bighorn Pokemon
DexDescription: Their antlers create a distortion in space that causes confusion.
  They were hunted for their magnificent antlers that were traded at high prices.
  This drove Stantlers close to extinction.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Sap Sipper
HomeSprite: SRD-stantler-HomeSprite.png
Image: stantler.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Amateur
  - '[[SRD-Stomp|Stomp]]'
- - Amateur
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Amateur
  - '[[SRD-Me First|Me First]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Amateur
  - '[[SRD-Role Play|Role Play]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Jump Kick|Jump Kick]]'
- - Ace
  - '[[SRD-Imprison|Imprison]]'
- - Ace
  - '[[SRD-Captivate|Captivate]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Disable|Disable]]'
- - Pro
  - '[[SRD-Megahorn|Megahorn]]'
- - Pro
  - '[[SRD-Thrash|Thrash]]'
Number: 234
ShuffleToken: SRD-stantler-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 71.2
  Pounds: 157.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-stantler-BookSprite.png|wsmall]]
> ![[SRD-stantler-HomeSprite.png]]
> ![[SRD-stantler-BoxSprite.png|htiny]]
> ![[SRD-stantler-ShuffleToken.png|wsmall]]


*Bighorn Pokemon*
*Their antlers create a distortion in space that causes confusion. They were hunted for their magnificent antlers that were traded at high prices. This drove Stantlers close to extinction.*

**DexID**:: 0234
**Name**:: Stantler
**Type**:: Normal
**Abilities**:: [[SRD-Intimidate|Intimidate]] / [[SRD-Frisk|Frisk]] ([[SRD-Sap Sipper|Sap Sipper]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'6" / 1.4m
**Weight**: 157.0lbs / 71.2kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Stantler.md"
flatten moves as T
where file.path = this.file.path
```
