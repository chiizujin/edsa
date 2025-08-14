Medical Monitor (1.4)

This agent adds a panel to the left of the screen that displays the
bacteria and toxin levels of all your creatures.

If any bacteria or toxins are found then a short alarm will sound and
the green cross on the edge of the tab will turn red.  Creatures are
checked about every 5 seconds but the alarm will not sound again until
all creatures have been healed.

The red light button can be used to turn off the monitor and the two
arrow buttons are used to scroll the window if there is more than one
page of text.  When the monitor is disabled the green/red cross will
turn grey.

Installation
------------
If you are upgrading from version 1.2 or earlier then you should
manually copy the included "medical monitor.catalogue" file into your
"Catalogue" folder.  This updates the agent help within the game
as this file will not be automatically updated if it already exists.

If this is the first version you have used then you can ignore the
"medical monitor.catalogue" file.

Version history
---------------
1.4
- The pain chemical is now monitored, which is a useful indication of
  a creature being hit, which can lead to death.  This chemical has a
  lower warning threshold of 10, rather than the 20 of all the
  other chemicals monitored.
1.3
- Fixed an incorrect display in some cases.  If an ill creature was
  found after another ill creature of the same name then the
  information for both of them would display as one name.
- The display now updates straight away when injected, rather than
  waiting for the first timed check.
- Added support for Ettins, Grendels and Geats.  The display of any of
  these (as well as Norns) can be toggled on and off individually.
- The agent can now be injected using the C3 creator machine without
  causing errors (or killing the machine if auto-kill is enabled).
1.2
- The Medical Monitor no longer appears on remote cameras.
- The agent now only allows one Medical Monitor to be in the world.
- Medical Monitor is aware of Norn Stats - whichever is installed
  first will be positioned lowest down on the screen.
- Unnamed Norns are now displayed with the name "(Unnamed)".
1.1
- CTRL+4 can now be used to open/close the panel.
- Dead Norns are now marked with (D) after the name.
- Removed the "Checking..." text that flashes up when the agent is
  checking the Norns.

Emmental
https://github.com/chiizujin/edsa
