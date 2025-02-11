---
Ability1: Thick Fat
Ability2: Guts
BookSprite: SRD-makuhita-BookSprite.png
BoxSprite: SRD-makuhita-BoxSprite.png
DexCategory: Guts Pokemon
DexDescription: A tenacious Pokemon that will get back up no matter how many times
  he gets knocked down. They have a tireless spirit, and never give up hope. Makuhitas
  put all their hearts into everything they do.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Hariyama]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Sheer Force
HomeSprite: SRD-makuhita-HomeSprite.png
Image: makuhita.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Arm Thrust|Arm Thrust]]'
- - Beginner
  - '[[SRD-Vital Throw|Vital Throw]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fake Out|Fake Out]]'
- - Amateur
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Amateur
  - '[[SRD-Knock Off|Knock Off]]'
- - Amateur
  - '[[SRD-Smelling Salts|Smelling Salts]]'
- - Amateur
  - '[[SRD-Belly Drum|Belly Drum]]'
- - Amateur
  - '[[SRD-Force Palm|Force Palm]]'
- - Amateur
  - '[[SRD-Seismic Toss|Seismic Toss]]'
- - Amateur
  - '[[SRD-Wake-Up Slap|Wake-Up Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Endure|Endure]]'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - Ace
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Pro
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Pro
  - '[[SRD-Detect|Detect]]'
Number: 296
ShuffleToken: SRD-makuhita-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 86.4
  Pounds: 190.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-makuhita-BookSprite.png|wsmall]]
> ![[SRD-makuhita-HomeSprite.png]]
> ![[SRD-makuhita-BoxSprite.png|htiny]]
> ![[SRD-makuhita-ShuffleToken.png|wsmall]]


*Guts Pokemon*
*A tenacious Pokemon that will get back up no matter how many times he gets knocked down. They have a tireless spirit, and never give up hope. Makuhitas put all their hearts into everything they do.*

**DexID**:: 0296
**Name**:: Makuhita
**Type**:: Fighting
**Abilities**:: [[SRD-Thick Fat|Thick Fat]] / [[SRD-Guts|Guts]] ([[SRD-Sheer Force|Sheer Force]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 3'3" / 1.0m
**Weight**: 190.5lbs / 86.4kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Hariyama]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Makuhita.md"
flatten moves as T
where file.path = this.file.path
```
