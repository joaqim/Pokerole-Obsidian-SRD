---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  SwitcherMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: The user teleports, switching its place with someone.
Effect: User switches back. Choose another Pokemon to take its place. It will be ready
  to fight on the next Round. Switcher Move.
Name: Ally Switch
Power: 0
Target: One Ally
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