---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Priority: 4
Category: Support
Damage1: ''
Damage2: ''
Description: The user quickly creates a barrier that reflects any minor attack, status
  condition, or dirty triick the foe might have wanted to use.
Effect: Priority 4. Redirect the effects of a Support Move that would affect the user
  or its side of the battlefield towards the foe's (ie. The foe used Stealth Rock,
  with Magic Coat it will now affect the foe's side instead of yours).
Name: Magic Coat
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