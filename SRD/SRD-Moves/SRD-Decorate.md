---
Accuracy1: Beauty
Accuracy2: Nature
AddedEffects:
  StatChanges:
  - Affects: Target
    Stages: 2
    Stats:
    - Strength
    - Special
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: Using some frosting the Pokemon decorates their target to look bigger,
  more powerful, and incredibly delicious!
Effect: Increase the Strength and Special of One Ally by 2
Name: Decorate
Power: 0
Target: One Ally
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