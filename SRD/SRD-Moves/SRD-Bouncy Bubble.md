---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Heal:
    Percentage: 0.5
    Target: User
    Type: Leech
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The user shoots bubbles at its target, the bubbles fill up with fresh
  water upon contact and bounce back towards the user. Should you drink the water
  inside? Who cares? It's fun!
Effect: The user restores HP equal to half the damage dealt, rounded down. If the
  user of this Move is at its Final Stage of Evolution, this move fails.
Name: Bouncy Bubble
Power: 3
Target: Foe
Type: Water
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