---
Accuracy1: Tough
Accuracy2: Perform
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -2
    Stats:
    - SpDef
Attributes:
  SoundBased: true
Category: Support
Damage1: ''
Damage2: ''
Description: The user produces a horrible noise that impedes the foe from focusing
  on the fight, leaving it vulnerable to attacks.
Effect: Sound Based. Reduce the foe's Special Defense by 2.
Name: Metal Sound
Power: 0
Target: Foe
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