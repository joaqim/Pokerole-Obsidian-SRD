---
Accuracy1: Will
Accuracy2: Channel
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
Category: Physical
Damage1: ''
Damage2: ''
Description: With pure willpower, the user struggles with its foe despite the pain
Effect: Roll Damage equal to the Difference between user's Full HP and its Current
  HP (up to 10). User cannot reduce the target's HP to lower than its own remaining
  HP. Ignore foe's Defenses.
Name: Endeavor
Power: 0
Target: Foe
Type: Normal
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