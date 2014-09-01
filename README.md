DockingPlugin
=============
The docking plugin for Space Engineers.  Requires SE Server Extensions.

Installation
============
Extract the DockingPlugin directory and put it into your Mods directory

Usage
=====
- Create a Docking Zone by creating a square with 4 beacons.  This defines your docking zone.  The zone can be on a station or large ship.  You must name all 4 beacons the same thing in order to use the docking zone.

- The docking zone beacons must be 100% built.
    
Docking
=======
Once you've defined a docking zone, you may move a small ship into the zone for docking.  There are many rules involved in docking that will be listed below.
    
    - Use the command /dock dock <dockingZoneName> to initiate the dock.
    
Docking Rules
=============
    - The small ship must be inside the docking zone when the docking command is issued.
    - The docking zone must be owned by the player docking it or
    - The docking zone must be shared to everyone in faction and the player must be in the faction
    - The small ship must be less than half the mass of the station / small ship
    - The small ship must fit inside the docking zone.  You must build the zone large enough to contain the ship.
    - Docking zone can not overlap or intersect each other.  They must be separate.
    - Only 1 ship can dock in a docking zone at a time.
    - The small ship can not have a pilot.
    - If a beacon in the docking zone is destroyed, so is your docked ship.
    - If the carrier is destroyed, so is your docked ship.
    
Undocking
=========
    - Use the command /dock undock <dockingZoneName> to undock a docked ship
    
Undocking Rules
===============
    - The carrier can not have a pilot.


Other Commands
==============
    - Use the command /dock list <dockingZoneName> to list if there are ships in the docking zone.
    - Use the command /dock validate <dockingZoneName> to see if a docking zone is valid before completing it's beacon.
    
    
    

    
