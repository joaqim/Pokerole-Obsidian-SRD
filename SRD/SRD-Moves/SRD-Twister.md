---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 2
    Type: Flinch
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The Pokemon lets out a spiral current that surrounds the foes. They can't
  move until they free themselves from this terrible whirlwind.
Effect: Roll 2 Chance Dice to Flinch the foes.
Name: Twister
Power: 2
Target: Foe
Type: Dragon
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