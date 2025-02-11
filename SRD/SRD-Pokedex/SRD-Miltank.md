---
Ability1: Thick Fat
Ability2: Scrappy
BookSprite: SRD-miltank-BookSprite.png
BoxSprite: SRD-miltank-BoxSprite.png
DexCategory: Milk Cow Pokemon
DexDescription: Their male counterpart is Tauros. A Miltank's milk is full of nutrients
  that may heal the sick and the injured, and they can produce up to 5 gallons a day.
  Healing serious injuries may require a lot of milk.
EventAbilities: ''
Evolutions: []
GenderType: F
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Sap Sipper
HomeSprite: SRD-miltank-HomeSprite.png
Image: miltank.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Beginner
  - '[[SRD-Stomp|Stomp]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Milk Drink|Milk Drink]]'
- - Amateur
  - '[[SRD-Bide|Bide]]'
- - Amateur
  - '[[SRD-Rollout|Rollout]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Captivate|Captivate]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - Ace
  - '[[SRD-Heal Bell|Heal Bell]]'
- - Ace
  - '[[SRD-Wake-Up Slap|Wake-Up Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Belch|Belch]]'
- - Pro
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Pro
  - '[[SRD-Mega Kick|Mega Kick]]'
Number: 241
ShuffleToken: SRD-miltank-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 75.5
  Pounds: 166.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-miltank-BookSprite.png|wsmall]]
> ![[SRD-miltank-HomeSprite.png]]
> ![[SRD-miltank-BoxSprite.png|htiny]]
> ![[SRD-miltank-ShuffleToken.png|wsmall]]


*Milk Cow Pokemon*
*Their male counterpart is Tauros. A Miltank's milk is full of nutrients that may heal the sick and the injured, and they can produce up to 5 gallons a day. Healing serious injuries may require a lot of milk.*

**DexID**:: 0241
**Name**:: Miltank
**Type**:: Normal
**Abilities**:: [[SRD-Thick Fat|Thick Fat]] / [[SRD-Scrappy|Scrappy]] ([[SRD-Sap Sipper|Sap Sipper]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 166.4lbs / 75.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Miltank.md"
flatten moves as T
where file.path = this.file.path
```
