---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 5
    Type: BadlyPoison
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: The Pokemon bites the foe and injects its poison directly through its
  fangs. After that it just waits for the poison to slowly take care of its foe.
Effect: Roll 5 Chance Dice to Badly Poison the Foe.
Name: Poison Fang
Power: 2
Target: Foe
Type: Poison
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