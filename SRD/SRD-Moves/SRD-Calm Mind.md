---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 1
    Stats:
    - Special
    - SpDef
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user quietly calms its spirit to strengthen its mind and body.
Effect: Increase the User's Special and Sp. Defense.
Name: Calm Mind
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