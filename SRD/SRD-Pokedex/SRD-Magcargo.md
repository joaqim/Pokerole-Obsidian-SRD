---
Ability1: Magma Armor
Ability2: Flame Body
BookSprite: SRD-magcargo-BookSprite.png
BoxSprite: SRD-magcargo-BoxSprite.png
DexCategory: Lava Pokemon
DexDescription: Their shell is molten body that cooled off and hardened, it may appear
  solid, but it may burst into flames with a single touch. Water vaporizes on contact
  and rain turns into a cloud of steam.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Slugma]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Weak Armor
HomeSprite: SRD-magcargo-HomeSprite.png
Image: magcargo.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Yawn|Yawn]]'
- - Starter
  - '[[SRD-Smog|Smog]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rock Throw|Rock Throw]]'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Harden|Harden]]'
- - Amateur
  - '[[SRD-Incinerate|Incinerate]]'
- - Amateur
  - '[[SRD-Recover|Recover]]'
- - Amateur
  - '[[SRD-Clear Smog|Clear Smog]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Lava Plume|Lava Plume]]'
- - Ace
  - '[[SRD-Earth Power|Earth Power]]'
- - Ace
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Ace
  - '[[SRD-Shell Smash|Shell Smash]]'
- - Ace
  - '[[SRD-Flamethrower|Flamethrower]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Inferno|Inferno]]'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Self Destruct|Self Destruct]]'
Number: 219
ShuffleToken: SRD-magcargo-ShuffleToken.png
Type1: Fire
Type2: Rock
Weight:
  Kilograms: 55.0
  Pounds: 121.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-magcargo-BookSprite.png|wsmall]]
> ![[SRD-magcargo-HomeSprite.png]]
> ![[SRD-magcargo-BoxSprite.png|htiny]]
> ![[SRD-magcargo-ShuffleToken.png|wsmall]]


*Lava Pokemon*
*Their shell is molten body that cooled off and hardened, it may appear solid, but it may burst into flames with a single touch. Water vaporizes on contact and rain turns into a cloud of steam.*

**DexID**:: 0219
**Name**:: Magcargo
**Type**:: Fire / Rock
**Abilities**:: [[SRD-Magma Armor|Magma Armor]] / [[SRD-Flame Body|Flame Body]] ([[SRD-Weak Armor|Weak Armor]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'6" / 0.8m
**Weight**: 121.3lbs / 55.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Slugma]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Magcargo.md"
flatten moves as T
where file.path = this.file.path
```
