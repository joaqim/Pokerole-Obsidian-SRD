---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 2
    Type: Poison
Attributes:
  PhysicalRanged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The Pokemon stabs the foe with its stinger, claws or spikes infused with
  poison.
Effect: Double action. Ranged. Roll 2 Chance Dice to Poison the foe per hit.
Name: Twineedle
Power: 1
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