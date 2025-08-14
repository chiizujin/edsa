Norn of Infertility (1.4)

This agent checks for possible immortal and fast-aging Norns and
attempts to keep them infertile.

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

Norns are checked every 5 minutes and are forced infertile every 20
seconds.  Infertility cannot be guaranteed, as fertility rises
constantly with time, though it should greatly reduce the chance of
pregnancies.  There is also the possibility that an immortal/fast-ager
will warp in and reproduce between the Norn of Infertility's checks.

Version history
---------------
1.4
- If the NoI tried to check a Norn as it left through the warp then
  an error would occur.  This should now be fixed.
- Fast-aging was being checked against the Youth stage instead of the
  Adult stage as was intended.  This was still a valid test but has
  now been changed to Adult stage.
- The NoI no longer falls through elevator shafts and upper level
  floors.
- The agent can now be injected using the C3 creator machine without
  causing errors (or killing the machine if auto-kill is enabled).
1.3
- Fixed an incorrect reference to a "reaper norn" sprite gallery.
  This agent was based on the Reaper Norn which was never released.
  Damn that cut-n-paste ;)
1.2
- Agent now uses OV variables instead of GAME variables.  The remove
  script still removes the legacy GAME variables.
1.1 (not released on site)
- Speeded up the checking of individual Norns using INST.

Emmental
https://github.com/chiizujin/edsa
