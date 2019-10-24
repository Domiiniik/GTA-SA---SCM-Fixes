# GTA-SA---SCM-Fixes Author: Noskillx
Fixing San Andreas 1.0 script issues while keeping original 1.0 savegames compatibility!

BIG Thanks:
OrionRS- Huge help with finding and fixing some of the issues.
Matt1010- GTA Forums Topic design.

LEGEND: 
Fixes marked with * require new game in order to take effect.

Current Fixes as of 24.10.2019 release:



-Fixed an issue in "Cesar Vialpando" where recruited gang members would be invisible during a cutscene in front of the Loco Low Co.

-Fixed another issue in "Cesar Vialpando" where npc traffic wouldn't have spawn after the cutscene in front of the Loco Low Co.

-Fixed a bug where Sweet wouldn't swap from passanger seat to the driver seat after the dialogue "You hit this up here and i'l go do another hood" in " Tagging up Turf"

-Added a workaround for the "Fender Ketchup" high FPS garage door issue - i'l no longer happen. (This is not a proper fix, the issue is not related to the script but to game's physics NOTE: This workaround will be removed as soon as "Framerate Vigilante" mod will fix it)

-Fixed parachute landing animation. (Since this fix script.img will be shipped as well because it needs streamed script to work WARNING: If you'l not replace script.img your game will crash while landing with the parachute)

-Fixed/restored PS2 train speed in the "intro" (It was too fast on PC resulting in cutscene looking a bit odd)

-Fixed incorrect Sweet's and Smoke's seat placements after the Cluckin' Bell "Smoke's order" cutscene in "Drive-thru" (originally Sweet was switching his seat position to the left side after the cutscene)

-Fixed Emmet's radar icon positions on the mini-map in "Sweet's girl" and "Running dog"

-*Fixed misplaced bribe pickup over the bridge in "Palomino Creek" (Previously developers used an - next to the y coordinates which made the bribe being stuck and un-accessible inside of a building in Doherty) 

-*Fixed misplaced Country Rifle spawn pickup inside of a SF Stadium (you could not pick it up without mods it was stuck inside of a building)

-Fixed bat spawn placement after killing the dealer in "Cleaning The Hood"

-Fixed Millie Perkins using a "Feltzer" instead of her usual car - "Club" during a jealous girlfriend event on the date.

-*Fixed missing Pizza Stack radar icon in Montgomery.

-*Fixed missing Barber icon in El Quebrados.

-*Fixed 3 IR Goggles pickups spawning only once after "Black Project" mission is passed. (if you pick them once they'd no longer respawn like a mission pickup which should not be the case)

-Fixed incorrect restaurant blip marked as a "Bar" on the radar during the "lets eat" date type with Barbara.


To-do list for further updates:
-Fix Vortex spawn in Bayside
-Fix LS Studio Pickups having an inapropriate height?
-Find a better solution for "Pizza&Barber icons fix"
-Fix Didier Sachs never being flagged as unlocked in ":OPENUP_101297"
-Add force_spawn flag for *these nudges* vehicle spawns.
-SCM Fix for Gym Glitch
-Fix for script removing blackboard object required by the import/export mission, causing crashes when CJ enters the area of the dry dock.
-Fix Madd Dog's basketball glitch
-Swap Katie to like "fast driving" instead as her dialogue suggests to drive faster.
-Fix for "It's not easy, but it's possible to trigger the Mafia Dept calls before the Are You Going... mission is available. If $1411 == 1 too early it will kill the Badlands mobile phone call thread and break the game progression"
-quadruple insane stunt fix
-Backport 2.0 scm fixes
-Fix bike school having incorrect medals.
-fix for wrong vehicle in the car-showroom in SF after Cesar missions?
-Maintain GTASnP.com and severe save-game editors compatibility.
