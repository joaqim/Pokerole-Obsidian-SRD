---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  PhysicalRanged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user quakes the ground plates. Some plates will move easier than
  others.
Effect: Ranged. 1 Dice to determine this Move's Power
Name: Magnitude
Power: 0
Target: Area
Type: Ground
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