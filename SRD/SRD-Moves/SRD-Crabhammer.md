---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  AccuracyReduction: 1
  HighCritical: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: A large pincer strikes with the power of a hammer. The demolition power
  is incredible.
Effect: High Critical. -1 Accuracy.
Name: Crabhammer
Power: 3
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