---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Target
    Type: Telekinesis
  - Affects: Target
    Type: Hovering
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user can manipulate objects and creatures with his mind. Pokemon
  and humans become easier to hit because their movements are restrained.
Effect: All attacks against the target have "Never Fail". The target is immune to
  Ground Moves. Lasts 2 Rounds.
Name: Telekinesis
Power: 0
Target: Foe
Type: Psychic
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