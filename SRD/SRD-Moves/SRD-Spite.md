---
Accuracy1: Will
Accuracy2: Intimidate
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The target feels overwhelmed by feelings of dread.
Effect: Reduce Target's Will to 1 point temporarily. Reset any effects it got from
  spending Will Points.
Name: Spite
Power: 0
Target: Foe
Type: Ghost
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