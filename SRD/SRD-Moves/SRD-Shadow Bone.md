---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 2
    Stages: -1
    Stats:
    - Def
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: The bone that this Pokemon uses as a weapon contains a spirit, that spirit
  may cling onto a victim, creating openings for its master.
Effect: Roll 2 Chance Dice to Reduce the Foe's Defense.
Name: Shadow Bone
Power: 3
Target: Foe
Type: Ghost
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