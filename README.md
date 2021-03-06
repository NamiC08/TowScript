# TowScript
A modified version of Asser90's tow script with multiple fixes and improvements.

## Important Note:
Script is designed to work with the regular GTA V FLATBED model, as well as with the modified flatbed, which I have included. To use this script with other flatbed models the placement values will have to be adjusted, this can be done by following the instructions at the top of the client.lua file.
ALL credit for the Mule flatbed (flatbed2) goes to TheF3nt0n. https://www.gta5-mods.com/vehicles/maibatsu-mule-recovery-add-on.
Credit for the flatbed3 model (also included in this script) goes to BrewCityBass.

## Features:
- Fixes attach/detach positions on both truck and ground. No more upside down cars when detaching!
- No more "jello" vehicles that stretch and warp when being towed.
- Can no longer detach a vehicle while the truck is moving or attach vehicles while they are moving.
- Vehicles will detach if the truck flips over.
- The vehicle that you want to tow, needs to be within 12m of your towtruck before you can start towing.
- Large vehicles cannot be towed (configurable in the **client.lua** file)
- You can have multiple towtrucks registered and have custom x,y,z offsets for the attatched vehicle.

## How it works:
- Using a trainer spawn `flatbed`, `flatbed2` or `flatbed3` and get in it.
- When you find a vehicle to tow, get out and walk up to the vehicle.
- While facing the vehicle type `/tow` in chat to attach the vehicle to the flatbed.
- Once at your destination, get out of the truck and type `/tow` in chat again to detach the vehicle from the flatbed.

## Known Issues:
If another player is next to you when the command is entered the vehicle may not attach/detach. **Ask them to step away.** 
The cause of this has been identified (the raycast is detecting the other player instead of the vehicle) and it is being worked on.

## Planned Features:
- None? Have a suggestion? Let me know.

## Already Implemented features:
- Restricted vehicles. (Keep people from towing large vehicles such as a helicopter or plane.)
- Restrict distance. (Vehicle to be towed and truck must be near each other.)

#### Join my Discord: http://discord.me/deziel0495
