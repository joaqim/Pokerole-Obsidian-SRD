---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Target
    Type: TarShot
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Dexterity
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon gushes a blob of black tar over its foe. The unfortunate
  voctim can barely move afterwards, keep it away from fire sources, tar is extrmely
  flammable.
Effect: Reduce the foe's Dexterity. Until the end of the Scene Fire Type Moves will
  deal Super-Effective damage against the foe.
Name: Tar Shot
Power: 0
Target: Foe
Type: Rock
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