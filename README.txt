4.2.2
General-

- Fixed melee weapons standing straight up.
- Fixed bile bombs spawning in places they shouldn't
- Reverted the melee weapon reduction change.
- Players can now easily communicate some game events using !autocom. (This is an early version of this feature, much more will be added later)
- Disabling lag compensation is no longer allowed in Pro Mod. (Temporary fix to an exploit. In the future you will just not be allowed to toggle it.)
- Added caster addons support and improved camera control for spectators.
- Added custom bonesaw effects for a few players.
- Updated l4d2lib, fixing some error spams.

Map Changes-

Dark Carnival 3:
- Blocked god spot underneath the first ramp of the coaster.
- Blocked several shortcuts on the coaster.
- Pill cabinet max pills reduced from 4 to 2.
- Added 2 possible pill spawns to the coaster.
- Added a melee weapon at the bottom of the coaster.
No Mercy 3:
- The metal door after the event will now open 20 seconds after pressing the button, instead of never opening.


4.2.1
General-

- The 2014 Pro Mod Winter Event has come to an end. Don't be sad though, Spring is just around the corner!
- Updated Tank Rock Stumble Block plugin.
- Fixed local mute plugin not loading due to missing translation files.
- Changed local mute commands from !mute and !unmute to !smute and !sunmute to avoid conflicts.
- Updated GeoIP Database.
- Updated dozens of outdated retro stripper files.

Map Changes-

Dark Carnival 1:
- Blocked a stuck spot on top of the bridge semi truck.
- Added an ammo pile spawn in the corner motel room near the police car.
- Made the path to the motel roof spawn require less jumping.
Dark Carnival 2:
- Fixed Chargers getting stuck on the lip of the ramp charge-off at the ladder choke.
- Blocked witches from spawning during the event.
Dark Carnival 3:
- Blocked Suvivors from getting on the shelves in the room after the swan maintenence room, as common cannot path there.
Dark Carnival 4:
- Blocked Survivors from getting on top of the tents before the end saferoom, as common cannot path there.
- Fixed not always being able to charge, jockey, and pull survivors off the lower barn roof sections without getting blocked.
- Blocked witches from spawning during the event.
Dark Carnival 5:
- Fixed sometimes getting Tank-punch-stuck in ceiling clips in the stadium.
- Reduced the volume of overhead fireworks.
The Parish 2:
- Improved clipping on new wall on the right side of the park.
- Fixed getting stuck on an awning while climbing up an SI ladder during the event.
- Lowered witch max spawn % to 95% to prevent witches spawning in saferoom.
The Parish 5:
- Blocked Survivors from jumping onto the semi at the start.
- Fixed Survivors getting Tank punched onto the tall concrete blocks at the start.
- Fixed the 2nd finale tank never spawning.


4.2

- Fixed some incorrect hittable interactions.
- Updated Diescraper Redux files to support latest version.
- Removed a broken witch spawn on Hard Rain 3.
- Removed a broken witch spawn on Swamp Fever 2.
- Boomer hordes will now always be the same size.
- Fixed witches still taking damage from SI.
- Tank can no longer be stumbled while throwing a rock. (This fixes the ghost rock bug)
- You can now locally mute a player with !mute (!unmute to unmute them)
- Updated list of what will be displayed by the Skill Detect plugin.
- Improved a few aspects of infected AI.
- Fixed escape tanks still spawning on Parish 5. (Using a short term fix, looking for a long term alternative.)
- Removed clips around Parish 1 start saferoom.
- Jockeys will now play their bacteria sound upon spawning.
- You will now find less melee weapons throughout maps, and more deagles / pistols in their place.
- Removed the center pellet from the static shotgun spread.
- Fixed chargers chest bumping against survivors if they attempted to charge from too close.
- Fixed some instances where infected would not be be immune to being lit on fire.
- Added custom bonesaw effects for CCT3 winners.
- Added some holiday cheer to servers across the world.


4.1
General-

Witches:
- Witches no longer follow the same spawning limitations as tanks, allowing for a wider range of possible spawns
- Blocked infected friendly fire against witch, excluding tank
- Witch no longer respawns when killed by tank
- Survivors will now receive points if witch is killed by tank
- Witch bonus will no longer print to chat

Tanks:
- Fixed an exploit which allowed Tank to kill incapacitated survivors with random props that aren't supposed to do damage
- Reduced the possibility of hittables doing more than 1 damage instance per tank hit (This means that it's less likely for a log to roll on you and instantly kill you after only 1 tank hit)
- Infected bots will now be kicked 10 seconds after tank spawns if they are not capping a survivor
- Removed water slowdown change prints
- Added an audio cue for tank spawns
- Added a new print for tank spawns: "Tank is now in play"

Survivors:
- All melee weapon spawns are now single pickup
- You now receive your starting pills when the round goes live, rather than when you leave saferoom
- Shoving a special infected will now increase your fatigue by 1
- Restored hunter shove FOV to 30.
- Added static shotgun spread. Values are based off RedTown. (We will continue to look to improve it)
- Fixed all survivors using coach's grunt noise when using melee weapons

Special Infected:
- Infected ghost hurt is now enabled after the round goes live
- Infected ghost warp rebound from Mouse 2 to Reload
- Despawning a special infected will now give you half of your missing HP back (This does not mean half of your max hp)
- Infected can no longer be lit on fire (They will however still take damage while standing in fire)
- Fixed hunters being able to instantly repounce after being shoved

Miscellaneous:
- Removed triggers that forced players to crouch near vents/holes
- Remade stripper path to better cater to side configs using unique stripper folders
- Pro Mod no longer uses the Entity Remover module from confogl (All functions have been replaced by better options)


Map Changes-

Dark Carnival 1:
- Unlocked the motel rooftop for SI
- Blocked the motel rooftop for Survivors
- Added two paths onto the rooftop
- Added some "no entry" markers for SI, to specify where unremovable rooftop clips still remain
- Removed tree before the hill drop
- Blocked the top of a bush next to the campsite hill drop
Dark Carnival 2:
- Blocked the tops of the five porta potties after you leave the warehouse
- Blocked the tops of the two hedges after you leave the warehouse
- Removed sandbags at the start, replaced with an SI ladder (yellow pole)
- Added a ladder choke nerf similar to Parish 3 in hunters configs
Dark Carnival 3:
- The coaster will no longer collide with or damage players and NPCs
- Blocked an exploit to skip the event
- Removed a Valve invisible wall in the swan room
- Added a second shelf above the first to block a spot that commons cannot path to
- Improved clipping on the sides of the shelves in the swan room
- Blocked an unteleportably stuck spot in the swan room
- Improved clip alignment over the hanging fence in the tunnel
- Added a prop to cover up a broken infected ladder
- Blocked players from entering the vent alt path in hunters configs
Dark Carnival 4:
- You can now charge, jockey, and pull survivors off the lower barn roof sections without getting blocked. Removed plank props as they are no longer necessary
- Blocked Survivors from getting on the tops of the bushes after you leave the barns
- Added props to cover up a broken infected ladder
Dark Carnival 5:
- Blocked Survivors from getting hit onto the 9 metal support beams underneath the stadium roof
- Blocked the tops of the 5 upright soda machines around the usual camping spot
- Improved clipping around a trash bin at the top of the stadium
- Blocked an event camping spots under the open tents in hunters configs
Swamp Fever 3:
- Blocked witch spawns during the event as they were often far from the intended path
- Tank will now lose rage normally while survivors are in the saferoom on Swamp Fever 3
Swamp Fever 4:
- Removed a Valve invisible wall near the upstairs event camping area, giving SI access to a breakable wall
- Fixed custom max distance printing despite the distance being default
Hard Rain 1 and 4:
- Improved clipping on a fence near the 2nd floor one way drop on map 4
- Added a minor prop for detail
- Removed a few of the orange cones around map 1 end saferoom/map 4 opening saferoom
- Blocked the top of the fence for Survivors right outside map 1 end saferoom/map 4 end saferoom
Hard Rain 3:
- Blocked a witch spawn at the top of the elevator which could be killed before the door opened.
The Parish 1:
- Fixed pistol sometimes still falling into the water
- Removed a Valve invisible wall that partially blocked access to the end saferoom rooftop
- Added a prop to allow SI to access the end saferoom rooftop
- Added a prop to get out of an unteleportably stuck spot behind a fence
The Parish 2:
- Removed concrete wall props in the open area after the bus station
- Added a wall opposite the one in front of the restrooms in the park
- Additional tree in the park is now slimmer and harder to use as an LOS/juking spot
- Park will continue to be revamped and tweaked based on feedback
The Parish 3:
- Blocked a high tickrate jump onto a tall green fence before the 2nd story drop
- Fixed Survivors getting caught on an unclipped infected ladder
- Blocked early witch spawns that were prone to glitching out
The Parish 4:
- Blocked an event camping spot underneath the stairs in hunters configs
The Parish 5:
- Added an intro tank that will spawn when survivors hit the radio
- Tank will now lose rage while survivors are in the saferoom on Parish 5
- Removed all of the reduced damage cars from the "tank arena" portion of the bridge
- Added a full damage hittable car to the "tank arena" portion of the bridge
- Increased pill count in tank arena from 2 to 4
- Removed the maze of balance after the bridge
- Removed escape tanks
- Increased map distance to 600
Death Toll 1:
- Added a static ammo pile near the end of the tunnel
Death Toll 2:
- Blocked an event camping spot in the rescue closet in hunters configs
Death Toll 3:
- Blocked a high tickrate shortcut to skip the train choke
Death Toll 4:
- Removed 4 pointless pill spawns at the very end
- Fixed pills spawning in the end saferoom
- Blocked a bunch of god-spot shelves in the warehouse behind the convienience store
Dead Air 3:
- Blocked an event camping spot under the pipes in hunters configs
- Blocked an event camping spot in the rescue closet in hunters configs
Dead Air 4:
- Fixed too many commons spawning during the event in 1v1 configs
- Blocked an event camping spot under some stairs in hunter configs
- You will no longer get pushed by the moving event van
Blood Harvest 3:
- Fixed too many commons spawning during the event in 1v1 configs
Blood Harvest 4:
- Removed a pointless invisible wall after exiting the warehouse
- Removed all props except one near end saferoom
Hard Rain: Downpour:
- Fixed stripper file being named incorrectly
- Fixed multiple Witches sometimes spawning


Side Configs-

1v1s:
- Replaced all pumpshotguns with chromes and smgs with silenced uzis
- Hunters can now pounce and scratch through doors instantly
- Common will now instantly destroy doors
- Gas can pour time reduced from 0.7 to 0.5
Reflux:
- Reflux now uses a modified version of Pro Mod's stripper files, rather than Retro's
Hunters:
- All hunter exclusive configs now share a unique stripper folder
Redtown:
- Pro Mod Redtown is now included in the Pro Mod package


4.0.4e
Blocked an out of map stuck spot on Undead Zone finale.
Increased Parish 1 map distance to 400.
Fixed players getting stuck after loading in during a pause.


4.0.4d
The !current command will now be much more accurate relative to tank spawns.
Fixed spawn timers not being properly set in 1v1 configs.
Fixed witches spawning in 1v1s.
Fixed people getting stuck on invis walls in the tunnel of love. (Dark Carnival 3)
Fixed "Fixing Waiting For Finale to Start issue for all infected" printing every round.
Unblocked an early tank spawn on Dark Blood map 2.
Tank will still lose rage while survivors are in saferoom on Dark Blood Map 2.
Blocked tank spawning while survivors are underwater on Dark Blood map 2.
Any tank that spawns after survivors have rode the lift up on Dark Blood map 2 will be spawned near the end saferoom, to give survivors breathing room.
Re-blocked early tanks on Dark Blood map 3.
Unblocked event tanks on Dark Blood 3.
Any tank that spawns after survivors have started the event on Dark Blood map 3 will be spawned at the end saferoom, to give survivors breathing room.
Made it much easier for tank to get out of a "stuck spot" on Dark Blood finale.
Removed all fireworks from Arena Of The Dead.
Removed an unbreakable freezer door from Urban Flight 1.
Made a few (interior) panes of glass breakable on Diescraper Redux Finale.
Fixed a tank stuck spot on Undead Zone finale.


4.0.4c
General-
- Fixed gascans spawning on some peoples servers.
- Vote kick ban time reduced from 5 minutes to 1 in all Pro Mod configs.
- Added support for a shared plugins file. All Pro Mod configs will read from "sharedplugins.cfg" in your left4dead2/cfg/ folder.
- Improved shadowing on a lot of props.
- Cleaned up stripper files.

Map Changes-
Swamp Fever 2:
- Added a spawn near the usual event camping area
- Reduced props near the shack after event
Swamp Fever 4:
- Improved clipping on fallen log that leads to a rooftop (you will no longer get stuck on it)
- Fixed a stuck spot under the planks that lead to the roof
- Blocked Survivors from getting on some bushes near where you enter the town
- Blocked Survivors from climbing the barrel stack intended for SI
- Removed an unecessary prop in the town
- Blocked Survivors from getting punched onto a tall bush in the plantation backyard
- There will now always be a Chrome Shotgun and Silenced SMG in the mansion
- Added an ammo pile and a propane spawn in the plantation backyard
Hard Rain 1 and 5:
- Removed unbreakable porta potty door
Dark Carnival 3:
- You will no longer get stuck inside swans in the Tunnel of Love
- Blocked a high-tickrate-only shortcut that would let you jump to the second level in the swan room from the ground level (not the generator shortcut)
- Blocked Survivors from getting punched onto a water tank in the swan room
Dark Carnival 4:
- Improved clipping on white fences surrounding saferoom
- Removed unbreakable porta potty doors
- Reduced viability of fighting Tank in the saferoom
- Tank will now lose rage normally while survivors are in the saferoom
- Moustachio horde can no longer be triggered by tank

Side configs-
- Updated all side configs to have the most recent CCT changes.
- Pro Mod 1v1 and 1v1 Hunters no longer have witches. (Deadman still has both witches and tanks.)
- Common limit reduced from 7 to 6 in all 1v1 configs.
- Mega Mob size reduced from 12 to 10 in all 1v1 configs.
- Gascan pour time reduced to 0.7 in all 1v1 configs.
- Deadstop field of view reduced to 15 in all 1v1 configs.
- Fixed Deadman not having proper spawn timers and damage per pounce.
- Reduced Jockey HP in Pro Mod 1v1 to 250.
- Added chargers to Pro Mod 1v1. They have 450 hp, 6 second cooldown on charge, 0 damage on the first scratch, and 5 damage on any scratches after that.

CCT-
- Survivors can no longer fall out the side of the lift on Arena of the Dead map 3.
- Removed all color correction from Undead Zone.
- Fixed error prop not being properly hidden on Undead Zone 1.
- Removed 2nd event from Undead Zone 1.
- Blocked survivors getting punched over a fence that they couldn't get back from on Undead Zone 2.
- Fixed weird shadowing of a prop on Undead Zone 3.
- Blocked survivors climbing on the metal rail we added for SI on Undead Zone 3.
- Flickering lights on Undead Zone 4 are now constant to improve FPS.
- Blocked instant tank spawn on Undead Zone 4.
- Fixed infected being unable to spawn on 2nd half of Urban Flight Finale.
- Removed an extra pill spawn from Urban Flight Finale.
- Fixed a broken ladder on Urban Flight Finale.
- Unblocked early tanks on Dark Blood map 3.
- Blocked event tanks on Dark Blood map 3.
- Survivors no longer have to climb the ladder of doom on Dark Blood Finale. The gascans have been moved to more reasonable places.
- Fixed infected not being able to spawn behind some bushes on Open Road 2.
- Fixed infected not being able to spawn behind some bushes on Open Road 4.
- Fixed the shadows of some props on Open Road 4.


4.0.4b
Undocumented 1v1 config update for a tourney. Properly documented under 4.0.4c


4.0.4a
Opened an alternate path on Urban Flight 2 which should shorten the length of the map by a bit.
Removed extra gascans from Urban Flight finale.
Removed some possible extra pill spawns from Urban Flight finale.
Removed endless horde on Undead Zone 2.
Added a way for infected to get out of a stuck spot on Undead Zone finale.
Added an ammo pile in the hangar where pills are on Undead Zone finale.
Removed possible medkit spawns from Diescraper 3 start saferoom.
Reduced Diescraper 3 max distance to 700.
Added 2nd finale tank to Diescraper Finale.
Tank will now lose rage while survivors are in Arena of the Dead 2 map 2 saferoom.
Slightly nerfed the insane ladder choke on Dark Blood 2 finale.
Added melee weapons to Open Road 3 alarmed gun room.
Added more spawns to open plane area of Undead Zone map 3.
Added an ammo pile on Undead Zone map 3.
Reduced votekick ban duration from 5 minutes to 1 minute.


4.0.4
Added support for the final 2 CCT maps.
Added a print for maps where tank loses rage while survivors are in saferoom.
Enabled tank rage tickdown in Open Road 2 saferoom.
Increased Open Road 3 map distance to 600.
Fixed a couple spit blocks being missing.
Fixed Dark Blood 2 map 3's stripper file not working properly causing the map to be unplayable.
Increased bile duration vs infected to 8. (From 5)
Finished cleaning up configs, a documentation file will be added in the near future.


4.0.3
All configs included in the pro mod package now support the first 4 CCT3 maps.
Made several improvements / fixes to the CCT maps. (Full list here: http://pastebin.com/e6WNsd9y)
Added support for Hard Rain Downpour.
Significantly cleaned up some of the configs. (Will finish this in next update)
Godframe indicator is now enabled by default.
Reduced charger and hunter godframes to 1.8 (From 2.1)
Reduced smoker and jockey spit extra time to 0.5 (From 0.7)
Spit godframe ticks increased from 4 to 6. (Vanilla is 8)
Reduced AOE on survivor self bile to match AOE of regular use.
Hunters now do continuous damage ticks. (Similar to how jockeys do damage.)
Unblocked very early tanks on No Mercy 1. (10-25%)
Tanks will now lose rage normally in the following saferooms:
Dead Center 1, Hard Rain 2, No Mercy 1, No Mercy 5, Death Toll 1, Blood Harvest 2


4.0.2
Removed natural hordes.


4.0.1
Fixed smokers not having spit godframes.
Removed hittables weight change.
Increased Natural Horde timer to 100 seconds.
Increased Natural Horde common count from 25 to 27.


4.0
Side Config Clean Up:
Removed unused / outdated cvars from Retro.
Hunters and Jockeys now do 25 damage (+pounce damage) per pounce in 1v1 configs.
Spawn timers reduced to 1 second in 1v1 configs.
AI tanks will now be instantly killed in 2v2 and 3v3 configs.
Fixed quadcaps not working in Reflux.
Removed Pro Mod HR from the package.

Main Changes:
Hunter godframes increased to 2.1*
Charger godframes increased to 2.1*
Smokers spit immunity godframe increased to 0.7*
Jockey spit immunity godframe increased to 0.7*
Spit damage increased from 2 damage per tick to 3.*
Added back 1 bile bomb.**
Bile bombs duration vs player controlled infected reduced to 5. (Default 20)**
Bile bombs duration reduced to 10 seconds. (Default 20)**
Bile bombs can now affect survivors in the same way they would an infected. 10 second duration; 150 AOE. (Careful where you throw it!)**
Natural Horde timer reduced from 3600 to 70.**
Natural Horde timer will be reset every time a boom lands, or a boomer gets popped.**
Deagle limit increased to 2.*
Tanks no longer get slowed by punching an incapped survivor.
Increased Tank ban on No Mercy 3 from 42% to 55%.
Removed hittables from warehouse after event on No Mercy 3.
Survivors can no longer open the metal door after the event on No Mercy 3.
Blocked tank from 0-55% on No Mercy 5.
No Mercy 5 Saferoom will now always contain a Silenced SMG and Chrome Shotgun.
Added 2 melee weapons to No Mercy 5 saferoom.
Added an ammo pile to map room on Dead Center 1 to encourage teams to push out of saferoom for early tanks.
Removed the cop car at the bottom of the first hill on Dead Center 2.
Moved cola to the side closet (and removed the doors) on Dead Center 2 event.
Removed an inaccessible pill spawn from Hard Rain 2 and 3.
Removed 4 inaccessible pill spawns on Hard Rain 4.
Enabled "Fun Skill Prints" by default. (Jacob skeeted Grizz. Jacob Leveled Hib. Etc.)

*Only applies to Pro Mod.
**Only applies to Pro Mod and Reflux.