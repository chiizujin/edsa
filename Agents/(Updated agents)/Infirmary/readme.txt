Infirmary - Docking Station Update (1.2)

This is an update of the Creatures 3 Infirmary metaroom by Lis Morris to enable
it to be fully compatible with undocked Docking Station worlds. It is based on
version 1.3.

Changes to Infirmary
--------------------
- The entrance to the infirmary for undocked DS worlds is located the Cappilata
  hub. For docked C3/DS worlds it is in its original C3 location.
- The room bounds have been adjusted so that things don't disappear off the
  bottom of the screen.
- The room is now correctly assigned to its parent metaroom.
- The remove script has been updated, including stopping it throwing an error if
  the agent wasn't installed.
- Fixed the diagnostic tool displaying the incorrect information for the room
  Norn.
- The infirmary now ejects Norns if there is more than one in it after they are
  teleported in or dropped in by the hand.
- Fixed Docking Station throwing a script error if chemical values greater than
  255 were entered.
- Added a text-only version (infirmary.txt) of the original documentation
  (infirmary.rtf).

Notes
-----
-  The remove script will only remove Norns from the room, so make sure there
   are no Ettins, Grendels or Geats (or any other objects) in the room when
   removing.

Credits
-------
Original agent:          Lis Morris
DS compatibility update: Emmental

See the original documentation for additional credits.

Dedication by Lis Morris
------------------------
It may be considered a little odd to dedicate a few lines of computer code and
some pixels to a person, but in this case it seems apt. Max Jerome, better known
as Steerpike, created many items for the creatures community, and died, aged 47,
shortly after the first beta of this agent was completed, causing much grief
among Creatures users everywhere. Therefore, I’d like to dedicate this infirmary
to his memory. I hope you enjoy using it, and take a few moments to remember him
when you do.

---------------
1.2
- Removal script now corrects the DS favourite count. This only affects the
  removal so you do not need to remove and recreate the agent.
1.1
- Added missing dependency reference in installer that prevented iromcross2.c16
  installing.
  Note: You do not need to reinstall the agent if you have already installed it
  by manually copying iromcross2.c16 into the Images folder.

Emmental
https://github.com/chiizujin/edsa
