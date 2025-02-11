---
Ability1: Dazzling
Ability2: Strong Jaw
BookSprite: SRD-bruxish-BookSprite.png
BoxSprite: SRD-bruxish-BoxSprite.png
DexCategory: Gnash Teeth Pokemon
DexDescription: The protuberance on its head emits psychic waves that confuse its
  prey, while it is confused Bruxish grinds it with its sharp teeth. This grinding
  noise makes other Pokemon flee from the place in hurry.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Wonder Skin
HomeSprite: SRD-bruxish-HomeSprite.png
Image: bruxish.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Amateur
  - '[[SRD-Disable|Disable]]'
- - Amateur
  - '[[SRD-Psywave|Psywave]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psychic Fangs|Psychic Fangs]]'
- - Ace
  - '[[SRD-Synchronoise|Synchronoise]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Pro
  - '[[SRD-Poison Fang|Poison Fang]]'
- - Pro
  - '[[SRD-Waterfall|Waterfall]]'
Number: 779
ShuffleToken: SRD-bruxish-ShuffleToken.png
Type1: Water
Type2: Psychic
Weight:
  Kilograms: 19.0
  Pounds: 41.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-bruxish-BookSprite.png|wsmall]]
> ![[SRD-bruxish-HomeSprite.png]]
> ![[SRD-bruxish-BoxSprite.png|htiny]]
> ![[SRD-bruxish-ShuffleToken.png|wsmall]]


*Gnash Teeth Pokemon*
*The protuberance on its head emits psychic waves that confuse its prey, while it is confused Bruxish grinds it with its sharp teeth. This grinding noise makes other Pokemon flee from the place in hurry.*

**DexID**:: 0779
**Name**:: Bruxish
**Type**:: Water / Psychic
**Abilities**:: [[SRD-Dazzling|Dazzling]] / [[SRD-Strong Jaw|Strong Jaw]] ([[SRD-Wonder Skin|Wonder Skin]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'0" / 0.9m
**Weight**: 41.9lbs / 19.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Bruxish.md"
flatten moves as T
where file.path = this.file.path
```
