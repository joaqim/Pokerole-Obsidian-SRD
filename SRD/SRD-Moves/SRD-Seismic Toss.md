---
Accuracy1: Strength
Accuracy2: Athletic
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
Category: Physical
Damage1: ''
Damage2: ''
Description: The target gets launched up then falls face first into the ground, the
  stronger the user the higher the foe will be thrown.
Effect: Roll Damage Dice according to the User's Rank. 1 Dice at Starter Rank. 2 Dice
  at Beginner Rank.  3 dice at Amateur Rank.  4 Dice at Ace Rank.  5 Dice at Professional
  Rank. Ignores Defense.
Name: Seismic Toss
Power: 0
Target: Foe
Type: Fighting
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