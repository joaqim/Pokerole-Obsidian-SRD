---
Accuracy1: Clever
Accuracy2: Channel
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: With psychic suggestion, the target feels afflicted by the same status
  problems as the user.
Effect: Transfer the User's Status Ailments to the target. The user is now cured.
Name: Psycho Shift
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