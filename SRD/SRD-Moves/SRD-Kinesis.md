---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Accuracy
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: A basic psychic power to exert force on objects. You can touch, move,
  press, and affect simple objects to create distractions.
Effect: Lower the foe's Accuracy.
Name: Kinesis
Power: 0
Target: Foe
Type: Psychic
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