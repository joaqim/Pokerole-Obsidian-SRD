---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 3
    Stages: -1
    Stats:
    - Accuracy
Attributes:
  AccuracyReduction: 2
Category: Special
Damage1: Special
Damage2: ''
Description: The Pokemon shoots a ball made of mud that bursts on the target, some
  mud may get on its eyes.
Effect: Roll 3 Chance Dice to Reduce the Foe's Accuracy. -2 Accuracy.
Name: Mud Bomb
Power: 2
Target: Foe
Type: Ground
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