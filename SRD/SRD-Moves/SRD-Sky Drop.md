---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Charge: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user carries the opponent to the sky, then drops the target from
  that altitude.
Effect: Charge Move. While charging this move the Target is flinched. Flying Type
  Pokemon are immune to the Damage of this move. Lifting a target is restricted by
  the Strength of the User.
Name: Sky Drop
Power: 2
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