---
Accuracy1: Strength
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Lethal: true
  PhysicalRanged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The earth moves on its own, no attacker in sight. The floor crumbles
  and the ground shakes while engulfing its victims. From the rubble, lush trees emerge
  a short time after.
Effect: Lethal. Ranged. All Foes in Range.
Name: Land's Wrath
Power: 3
Target: All Foes
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