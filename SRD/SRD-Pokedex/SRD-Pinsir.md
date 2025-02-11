---
Ability1: Hyper Cutter
Ability2: Mold Breaker
BookSprite: SRD-pinsir-BookSprite.png
BoxSprite: SRD-pinsir-BoxSprite.png
DexCategory: Stagbeetle Pokemon
DexDescription: Their pincers are strong enough to shatter thick logs. Because they
  dislike cold, Pinsirs burrow and sleep under the ground on chilly nights. They like
  to eat sap and honey, but they are aggressive by nature.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Pinsirite
  Kind: Mega
  Pokemon: '[[SRD-Pinsir (Mega Form)]]'
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Moxie
HomeSprite: SRD-pinsir-HomeSprite.png
Image: pinsir.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Vice Grip|Vice Grip]]'
- - Starter
  - '[[SRD-Focus Energy|Focus Energy]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bind|Bind]]'
- - Beginner
  - '[[SRD-Seismic Toss|Seismic Toss]]'
- - Beginner
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Revenge|Revenge]]'
- - Amateur
  - '[[SRD-Brick Break|Brick Break]]'
- - Amateur
  - '[[SRD-Vital Throw|Vital Throw]]'
- - Amateur
  - '[[SRD-Double Hit|Double Hit]]'
- - Amateur
  - '[[SRD-Submission|Submission]]'
- - Amateur
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Amateur
  - '[[SRD-Storm Throw|Storm Throw]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - Ace
  - '[[SRD-Guillotine|Guillotine]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Feint Attack|Feint Attack]]'
Number: 127
ShuffleToken: SRD-pinsir-ShuffleToken.png
Type1: Bug
Type2: ''
Weight:
  Kilograms: 55.0
  Pounds: 121.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pinsir-BookSprite.png|wsmall]]
> ![[SRD-pinsir-HomeSprite.png]]
> ![[SRD-pinsir-BoxSprite.png|htiny]]
> ![[SRD-pinsir-ShuffleToken.png|wsmall]]


*Stagbeetle Pokemon*
*Their pincers are strong enough to shatter thick logs. Because they dislike cold, Pinsirs burrow and sleep under the ground on chilly nights. They like to eat sap and honey, but they are aggressive by nature.*

**DexID**:: 0127
**Name**:: Pinsir
**Type**:: Bug
**Abilities**:: [[SRD-Hyper Cutter|Hyper Cutter]] / [[SRD-Mold Breaker|Mold Breaker]] ([[SRD-Moxie|Moxie]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 121.3lbs / 55.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                    | Kind   | Item      |
|:----------|:---------------------------|:-------|:----------|
| To        | [[SRD-Pinsir (Mega Form)]] | Mega   | Pinsirite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Pinsir.md"
flatten moves as T
where file.path = this.file.path
```
