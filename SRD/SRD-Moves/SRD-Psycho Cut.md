---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  HighCritical: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: Create blades of psychic energy to tear down foes.
Effect: High Critical.
Name: Psycho Cut
Power: 3
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