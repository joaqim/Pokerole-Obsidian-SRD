---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Flinch
Attributes:
  Priority: 1
Category: Physical
Damage1: Strength
Damage2: ''
Description: While still preparing for battle, the user will suddenly attack the foe.
Effect: Priority 1. Flinch the foe. This move will only work the First Round the Pokemon
  is out in battle. From the second round on, it will fail automatically.
Name: Fake Out
Power: 2
Target: Foe
Type: Normal
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