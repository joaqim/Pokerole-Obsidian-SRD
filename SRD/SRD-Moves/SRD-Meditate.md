---
Accuracy1: Will
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 1
    Stats:
    - Strength
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon meditates to unleash a power that's been sleeping deep inside
  the user.
Effect: Increase the User's Strength
Name: Meditate
Power: 0
Target: User
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