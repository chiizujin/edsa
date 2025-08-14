Norn of Knowing (1.3)

This agent checks for possible immortal and fast-aging Norns.

It does this by checking 3 possible indicators:

1. Norns older than 9 hours may be immortal.
2. Norns with 2 or more toxins in their body over 95 may be immortal.
3. Norns that reached adult before they were 30 minutes old are
   probably fast-agers.

If any of these checks are matched then a "boing" sound will be heard
and the Norn's name that is displayed above the NoK will have 1 or
more extra letters added in front of it followed by a ! as follows:

O = Old
T = Toxins
A = Aging

Version history
---------------
1.3
- If the NoK tried to check a Norn as it left through the warp then
  an error would occur.  This should now be fixed.
- Fast-aging was being checked against the Youth stage instead of the
  Adult stage as was intended.  This was still a valid test but has
  now been changed to Adult stage.
- The NoK no longer falls through elevator shafts and upper level
  floors.
- The agent can now be injected using the C3 creator machine without
  causing errors (or killing the machine if auto-kill is enabled).
1.2
- Fixed the kill script to remove the Activate 1 script.
- Speeded up the checking of individual Norns using INST.
1.1
- Norns are now only checked if they are older than 5 seconds.  This is
  to prevent a "meta room" error occuring when trying to change the
  camera to new-borns.
- Dead Norns are no longer checked.
- The agent now appears in both the C3 and DS agent lists.

Emmental
https://github.com/chiizujin/edsa
