---
Accuracy1: Insight
Accuracy2: Allure
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user and the target swap their feelings of powerr and weakness, insecurity
  and courage, love and hate. Boosts are also swapped.
Effect: Switch any Trait Increase/Decrease with the target.
Name: Heart Swap
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