Medical Monitor (1.5)

Preamble
--------
Medical Monitor received an update for the CCSF in 2024 by SunlitMiracle, which
was distributed as a separate version. I have since fixed an old bug
(originating in the original version) in both versions and therefore, as of
version 1.5, both the original version (hereafter referred to as "Legacy") and
SunlitMiracle's version (hereafter referred to as "Update") are included in one
download.

See the file "SunlitMiracle's MM and NS updates.txt" for full details of the
changes made by SunlitMiracle.

Agent information
-----------------
This agent adds a panel to the left of the screen that displays information
about various chemical levels of all your creatures, such as bacteria and
toxins.

If any chemical levels are considered to be abnormal then a short alarm will
sound and the green cross on the edge of the tab will turn red. Creatures are
checked about every 5 seconds but the alarm will not sound again until all
creatures have been healed.

The red light button can be used to turn off the monitor and the two arrow
buttons are used to scroll the window if there is more than one page of text.
When the monitor is disabled the green/red cross will turn grey.

Installation
------------
If you have used any version (of either agent) prior to 1.4.2, then copy
"medical monitor.catalogue" to the game's "Catalogue" folder.

Optional but highly recommended (Update only)
---------------------------------------------
Download the Unofficial Chemicals Catalogue
https://eemfoo.org/archive/downloads/bb16 and Short Chem Names
https://eemfoo.org/archive/downloads/7412 to ensure chemicals are displayed
properly. Even if you don't use unofficial creatures with fan-created chemicals,
this is recommended due to Chemical 90, Wounded, not being named in the game's
catalogue files for some reason. Install in both the "Docking Station/Catalogue"
and the "Creatures 3/Catalogue" folders. The monitors are still functional
without this but several chemicals will show up as only numbers.

Credits
-------
- Original agent: Emmental.
- Update versions 1.4.1 & 1.4.2: SunlitMiracle.

Version history (Both versions)
-------------------------------
1.5
- Fixed operation of shortcut key (CTRL+4).
- Changed CALL to MESG WRIT.

Version history (Update by SunlitMiracle)
-----------------------------------------
1.4.2
- Adjustments to various detection thresholds to better reflect creatures'
  needs.
- Updated the in-game help file with new information, also added tooltips.
1.4.1
- Truncation of creature names longer than 16 characters; renamed (D) marker and
  made it its own trackable condition; non-Norns tracked by default
- Added tracking for: Pregnancy, Glycogen, Oxygen, Water, Air, ATP, Wounded,
  Hunger for Fat/Carbs/Protein, Coldness, Hotness
- Tracking of custom chemicals 110 (Body Heat), 130 (Tryptamine), Oxygenated
  Hemoglobin (221). Body Heat and Oxygenated Hemoglobin should ideally only
  trigger for True Warmbloods, but false positives and negatives are possible
  with mutations and certain custom breeds.
- Some chemicals display best with the Unoffical Chemical Names and Short Chem
  Names catalogues.

Version history (Legacy)
------------------------
1.4
- The pain chemical is now monitored, which is a useful indication of a creature
  being hit, which can lead to death. This chemical has a lower warning
  threshold of 10, rather than the 20 of all the other chemicals monitored.
1.3
- Fixed an incorrect display in some cases. If an ill creature was found after
  another ill creature of the same name then the information for both of them
  would display as one name.
- The display now updates straight away when injected, rather than waiting for
  the first timed check.
- Added support for Ettins, Grendels and Geats. The display of any of these (as
  well as Norns) can be toggled on and off individually.
- The agent can now be injected using the C3 creator machine without causing
  errors (or killing the machine if auto-kill is enabled).
1.2
- The Medical Monitor no longer appears on remote cameras.
- The agent now only allows one Medical Monitor to be in the world.
- Medical Monitor is aware of Norn Stats - whichever is installed first will be
  positioned lowest down on the screen.
- Unnamed Norns are now displayed with the name "(Unnamed)".
1.1
- CTRL+4 can now be used to open/close the panel.
- Dead Norns are now marked with (D) after the name.
- Removed the "Checking..." text that flashes up when the agent is checking the
  Norns.

Emmental
https://github.com/chiizujin/edsa
