---
Ability1: Oblivious
Ability2: Own Tempo
BookSprite: SRD-slowpoke-BookSprite.png
BoxSprite: SRD-slowpoke-BoxSprite.png
DexCategory: Dopey Pokemon
DexDescription: "It lives close to water. This Pokemon has a low intellect, and it\u2019\
  s slow to react to any stimuli. Its tail seeps a sweet substance it uses to lure\
  \ prey to eat. When the tip turns white shellders will be attracted to it."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Slowbro]]'
  Speed: Slow
- Evolves: To
  Item: King's Rock
  Kind: Trade
  Pokemon: '[[SRD-Slowking]]'
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Regenerator
HomeSprite: SRD-slowpoke-HomeSprite.png
Image: slowpoke.png
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
  - '[[SRD-Future Sight|Future Sight]]'
- - Pro
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Pro
  - '[[SRD-Icy Wind|Icy Wind]]'
Number: 79
ShuffleToken: SRD-slowpoke-ShuffleToken.png
Type1: Water
Type2: Psychic
Weight:
  Kilograms: 36.0
  Pounds: 79.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-slowpoke-BookSprite.png|wsmall]]
> ![[SRD-slowpoke-HomeSprite.png]]
> ![[SRD-slowpoke-BoxSprite.png|htiny]]
> ![[SRD-slowpoke-ShuffleToken.png|wsmall]]


*Dopey Pokemon*
*It lives close to water. This Pokemon has a low intellect, and it’s slow to react to any stimuli. Its tail seeps a sweet substance it uses to lure prey to eat. When the tip turns white shellders will be attracted to it.*

**DexID**:: 0079
**Name**:: Slowpoke
**Type**:: Water / Psychic
**Abilities**:: [[SRD-Oblivious|Oblivious]] / [[SRD-Own Tempo|Own Tempo]] ([[SRD-Regenerator|Regenerator]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 3'9" / 1.2m
**Weight**: 79.4lbs / 36.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   | Item        |
|:----------|:-----------------|:-------|:--------|:------------|
| To        | [[SRD-Slowbro]]  | Level  | Slow    |             |
| To        | [[SRD-Slowking]] | Trade  |         | King's Rock |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Slowpoke.md"
flatten moves as T
where file.path = this.file.path
```
