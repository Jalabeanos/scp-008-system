# Features
Toolgun setup tool to define the trigger door (or button/entity) and the infection zone(s) in-game, with a live preview.

Door-based release: SCP-008 is active for as long as the trigger door is open. Anyone already inside the zone, or who walks in while it's open, gets infected.

Hidden incubation: a random 30 second to 5 minute delay (configurable) before symptoms begin.

Symptoms: coughing, view punches, a red desaturated screen with blur that ramps up, and damage over time that never kills before the player turns.

Zombie transformation: after a while the player gets a zombie playermodel, loses all weapons except the claws, and gets 500-800 health.

SCP-008-2 SWEP: the zombie's claws. Anyone hit is infected.

SCP-500 entity: eat it to cure the infection and restore max health.

Saves per map, with admin console commands and a config file.
# Installation
Download this repository.
Put the scp008 folder into garrysmod/addons/.
Restart the server.
# Setup
Open the spawn menu, go to the toolgun, and choose SCP-008 => SCP-008 Setup. The tool is superadmin only by default. Pick a mode in the tool's settings panel.

Door mode (the thing that releases SCP-008)

Left click a door, button or other map entity to add it as a trigger. Click it again to remove it.
Reload while aiming at a trigger removes it.
The entity must be created by the map, so props spawned in-game can't be used.

Zone mode (the infection zone)

Left click one corner of the room (for example a floor corner).
Right click the opposite corner (for example the far ceiling corner). The zone is saved.
Reload deletes the zone you're standing in or aiming at. If you have a corner pending, reload cancels it.
You can create as many zones as you like.
