---
ns: PLAYER
---
## SET_PLAYER_WEAPON_DAMAGE_MODIFIER

```c
// 0xCE07B9F7817AADA3 0xB02C2F39
void SET_PLAYER_WEAPON_DAMAGE_MODIFIER(Player player, float modifier);
```

```
This modifies the damage value of all weapons and not just the selected/equipped weapon and you will have to restore all other weapons their damage else you will rig all the damage. Whether it is a multiplier or base damage is unknown.   
Based on tests, it is unlikely to be a multiplier.  
```

## Parameters
* **player**: 
* **modifier**: 

