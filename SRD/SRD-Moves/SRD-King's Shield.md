---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -2
    Stats:
    - Strength
Attributes:
  Priority: 3
  ShieldMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon uses a ghostly shield to protect itself. If the foe managed
  to touch it, the user will drain some of its lifeforce.
Effect: Priority 3. Shield. If the foe was using a Physical Move. Reduce the foe's
  Strength by 2. Reduce 3 Dice from the foe's Damage Pool.
Name: King's Shield
Power: 0
Target: User
Type: Steel
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