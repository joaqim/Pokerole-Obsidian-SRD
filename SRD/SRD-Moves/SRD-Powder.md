---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Powder
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The foe is fully covered with a flammable powder, a source of fire might
  ignite it with explosive results.
Effect: Add 3 Dice of Damage to the next Fire Type attack that hits the target.
Name: Powder
Power: 0
Target: Foe
Type: Bug
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