---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  NeverFail: true
Category: Special
Damage1: Special
Damage2: ''
Description: The user sends out a floating leaf that will pursue the target until
  it hits.
Effect: Never Fail.
Name: Magical Leaf
Power: 2
Target: Foe
Type: Grass
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