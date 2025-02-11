---
Ability1: Shell Armor
Ability2: ''
BookSprite: SRD-slowbro-mega-form-BookSprite.png
BoxSprite: SRD-slowbro-mega-form-BoxSprite.png
DexCategory: Hermit Crab Pokemon
DexDescription: "With the power of the Mega Stone the Shellder on its tail becomes\
  \ a bulletproof armor that swallows its host\u2019s whole body. Slowpoke doesn\u2019\
  t seem to mind and looks pretty comfy to nest inside."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Slowbronite
  Kind: Mega
  Pokemon: '[[SRD-Slowbro]]'
GenderType: ''
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: ''
HomeSprite: SRD-slowbro-mega-form-HomeSprite.png
Image: slowbro-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Yawn|Yawn]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Curse|Curse]]'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Confusion|Confusion]]'
- - Amateur
  - '[[SRD-Disable|Disable]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Slack Off|Slack Off]]'
- - Amateur
  - '[[SRD-Withdraw|Withdraw]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Ace
  - '[[SRD-Psych Up|Psych Up]]'
- - Ace
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Belly Drum|Belly Drum]]'
- - Pro
  - '[[SRD-Future Sight|Future Sight]]'
Number: 80
ShuffleToken: SRD-slowbro-mega-form-ShuffleToken.png
Type1: Water
Type2: Psychic
Weight:
  Kilograms: 120.0
  Pounds: 264.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-slowbro-mega-form-BookSprite.png|wsmall]]
> ![[SRD-slowbro-mega-form-HomeSprite.png]]
> ![[SRD-slowbro-mega-form-BoxSprite.png|htiny]]
> ![[SRD-slowbro-mega-form-ShuffleToken.png|wsmall]]


*Hermit Crab Pokemon*
*With the power of the Mega Stone the Shellder on its tail becomes a bulletproof armor that swallows its host’s whole body. Slowpoke doesn’t seem to mind and looks pretty comfy to nest inside.*

**DexID**:: 0080M
**Name**:: Slowbro (Mega Form)
**Type**:: Water / Psychic
**Abilities**:: [[SRD-Shell Armor|Shell Armor]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::4)/(MaxVitality::9)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'6" / 2.0m
**Weight**: 264.6lbs / 120.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Item        |
|:----------|:----------------|:-------|:------------|
| From      | [[SRD-Slowbro]] | Mega   | Slowbronite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Slowbro (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
