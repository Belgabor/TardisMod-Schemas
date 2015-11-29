# TardisMod-Schemas
Schemas for the Minecraft mod TardisMod ([Curse](http://www.curse.com/mc-mods/minecraft/230170-tardis-mod)/[MCF](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2420176-tardis-mod-updated-to-v0-99-on-13-08-2015))

In general I use the following abbreviations for basic layout variants. `O` is a dead end, `X` is a crossing (doors straight ahead, left and right), `I` is corridor style (door straight ahead) and `T` means T-junction style (three doors).

## Rooms
Various rooms for specific uses

### Big Farm Fixed
Originally by [NovaDrake711](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2420176-tardis-mod-updated-to-v0-99-on-13-08-2015?comment=1178), so all credit goes to them. I only fixed some minor inconsistencies in roundel placement

### Cellar
Rooms with a three high space below the floor to house potentially hidden things below the floor. Small version based on the Small Camber by [NovaDrake711](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2420176-tardis-mod-updated-to-v0-99-on-13-08-2015?comment=1178).

### LP Relay
Intended as a central relay for a Logistics Pipes setup inside the TARDIS. Central indented spot for the power junction, lots of roundels to connect inventory connector pipes to.

### Machines
Various rooms for machines along the walls with corresponding trenches for piping/conduits.

### Tanks
Rooms for full size RailCraft tanks. Offer plenty space above and below for cables and/or machines.


## Utility
Various corridors and elevators for tighter setups.

Corridors are desginated by internal length (blocks between the doors).
Some have a "niche" variant, those have one or two wall niches prepared to house an ME terminal or LP request table flush with the wall providing enough space for the necessary infrastructure.

Elevator nomeclatur is as follows:

`a b c`

```
a. Vertical size in small height steps (aka like the vanilla up/down corridors)
b. Number of intermediate levels
c. Level number, 1 being the bottom one, the elevator connects on
```

Example: `2 1 1` means the elevator is two "stories" big, has three stops (bottom, middle, top) and connects on the bottommost level. `2 0 1` whould basically match the vanilla "Up Further" corridor.

Vanilla elevators more closely follow the style of the original up/down corridors while offering a tighter setup.

