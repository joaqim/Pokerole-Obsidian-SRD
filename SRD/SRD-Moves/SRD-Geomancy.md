---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects: {}
Attributes:
  Charge: true
Category: Support
Damage1: ''
Damage2: ''
Description: Through a mystical connection this Pokemon absorbs the life force of
  earth itself to increase its power.
Effect: Charge Move. The user charges, then Increases by 2 its Dexterity, Special
  and Sp. Defense scores on its next Turn.
Name: Geomancy
Power: 0
Target: User
Type: Fairy
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