---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 5
    Stages: -1
    Stats:
    - Accuracy
Attributes:
  AccuracyReduction: 2
Category: Special
Damage1: Special
Damage2: ''
Description: The user sprays ink at the target's face to obstruct its vison.
Effect: Roll 5 Chance Dice to Reduce the foe's Accuracy. -2 Accuracy.
Name: Octazooka
Power: 2
Target: Foe
Type: Water
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