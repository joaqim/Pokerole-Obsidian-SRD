---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The user shines a powerful flash that hurts the eyes of everyone watching
  it.
Effect: '-'
Name: Dazzling Gleam
Power: 3
Target: All Foes
Type: Fairy
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