---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  AccuracyReduction: 1
  AlwaysCrit: true
Category: Special
Damage1: Special
Damage2: ''
Description: The user shoots a gelid breath against the target that sends a chill
  through the spine. The sudden change of temperature can bring anyone to its knees.
Effect: This Move is always a Critical Hit and it gets the proper bonus for it. -1
  Accuracy.
Name: Frost Breath
Power: 2
Target: Foe
Type: Ice
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