---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Recoil: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The Pokemon flies straight at the foe at full speed, the collision might
  hurt both of them.
Effect: Recoil.
Name: Brave Bird
Power: 5
Target: Foe
Type: Flying
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