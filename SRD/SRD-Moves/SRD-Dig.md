---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: User
    Type: Dig
Attributes:
  Charge: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user digs a tunnel on the ground and attacks while coming out from
  below.
Effect: Charge Move. While charging this move, the User will be out of range. Can
  be hit by Earthquake, Magnitude, or a similar move.
Name: Dig
Power: 3
Target: Foe
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