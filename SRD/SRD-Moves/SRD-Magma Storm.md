---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Block
Attributes:
  AccuracyReduction: 2
  BlockDamagePool: 3
Category: Special
Damage1: Special
Damage2: ''
Description: The Pokemon shoots a fiery eruption to its foe. Unable to escape and
  surrounded by the unbearable heat the foe's survival is at risk.
Effect: Blocks. Roll 3 Damage Dice at the end of each Round. Lasts 4 Rounds. -2 Accuracy.
Name: Magma Storm
Power: 4
Target: Foe
Type: Fire
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