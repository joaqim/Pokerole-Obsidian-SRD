---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: -2
    Stats:
    - Special
Attributes:
  AccuracyReduction: 1
  Lethal: true
Category: Special
Damage1: Special
Damage2: ''
Description: The Pokemon releases an explosion of all of its concentrated psychic
  power in a devastating explosion, afterwards the user will be extremely tired.
Effect: Lethal. Reduce User's Special by 2. -1 Accuracy.
Name: Psycho Boost
Power: 6
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