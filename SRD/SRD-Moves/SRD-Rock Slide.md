---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Flinch
Attributes:
  AccuracyReduction: 1
  PhysicalRanged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The Pokemon creates a slide of falling rocks against its foes that may
  leave them crushed below the rubble.
Effect: Ranged. Roll 3 Chance Dice to Flinch those affected. -1 Accuracy.
Name: Rock Slide
Power: 3
Target: All Foes
Type: Rock
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Category          | Power          |
| ------------- | --------------- | ----------------  | -------------- |
| `= this.Type` | `= this.Target` | `= this.Category` | `= this.Power` | 

**Effect:** `= this.Effect`