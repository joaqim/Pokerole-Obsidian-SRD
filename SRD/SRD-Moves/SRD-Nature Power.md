---
Accuracy1: Special
Accuracy2: Nature
AddedEffects: {}
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The Pokemon makes use of the terrain and asks the nature for aid in battle.
Effect: The type of this move is determined by the environment. See Nature Power p.432
  for more info.
Name: Nature Power
Power: 3
Target: Foe
Type: Normal
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