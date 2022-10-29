# [TF2] Smarter Spawns

**Version 1.0.1**

## Description:
Players in spawns who are being attacked from outside of spawn will take reduced damage.
Players outside spawn being attacked from players inside spawn will also take reduced damage.
Damage scaling is configurable and can also be increased instead of reduced.
## Cvars:
- **smarter_spawns**
  - Plugin Version
- **smarter_spawns_damage_inspawn**
  - The damage percentage players inside spawn will take from players outside.
  - Min: 0.0
   - Max: 2.0
  - Default: 0.25 (or 25% of total damage)
- **smarter_spawns_damage_outsidespawn**
	- The damage percentage players outside spawn will take from players inside.
	- Min: 0.0
	- Max: 2.0
	- Default: 0.50 (or 50% of total damage)

## Install Instructions:
1. Place **SmarterSpawns.smx** into your addons/sourcemod/plugins/ folder.


## Notes:
This plugin uses the func_respawnroom entity to detect if a player is inside or outside of spawn. If your map doesn't have them or is sloppy with them, it's your problem. Don't whine when it doesn't do anything.

## Version History:
- **V1.0.0**
	- Initial Release
- **V1.0.1**
	- Minor optimizations
