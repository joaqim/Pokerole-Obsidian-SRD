---
Ability1: Torrent
Ability2: ''
BookSprite: SRD-feraligatr-BookSprite.png
BoxSprite: SRD-feraligatr-BoxSprite.png
DexCategory: Big Jaw Pokemon
DexDescription: While in the water, it opens its big jaw to intimidate anyone coming
  close. Whenever it bites, it shakes its head and savagely rolls to tear up its prey.
  It is a very dangerous Pokemon. Approach with caution
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Croconaw]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 7.5
  Meters: 2.3
HiddenAbility: Sheer Force
HomeSprite: SRD-feraligatr-HomeSprite.png
Image: feraligatr.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Rage|Rage]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Pro
  - '[[SRD-Hydro Cannon|Hydro Cannon]]'
- - Pro
  - '[[SRD-Metal Claw|Metal Claw]]'
Number: 160
ShuffleToken: SRD-feraligatr-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 88.8
  Pounds: 195.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-feraligatr-BookSprite.png|wsmall]]
> ![[SRD-feraligatr-HomeSprite.png]]
> ![[SRD-feraligatr-BoxSprite.png|htiny]]
> ![[SRD-feraligatr-ShuffleToken.png|wsmall]]


*Big Jaw Pokemon*
*While in the water, it opens its big jaw to intimidate anyone coming close. Whenever it bites, it shakes its head and savagely rolls to tear up its prey. It is a very dangerous Pokemon. Approach with caution*

**DexID**:: 0160
**Name**:: Feraligatr
**Type**:: Water
**Abilities**:: [[SRD-Torrent|Torrent]] ([[SRD-Sheer Force|Sheer Force]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 7'5" / 2.3m
**Weight**: 195.8lbs / 88.8kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Croconaw]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Feraligatr.md"
flatten moves as T
where file.path = this.file.path
```
