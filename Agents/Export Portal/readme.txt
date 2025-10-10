Export Portal (1.1)

This is a portal that works in a similar manner to the warp portals except that
it exports creatures instead of sending them through the warp.

The files containing exported creatures can be found in the game's "My
Creatures" folder.

Notes
-----
- The Export Portal is aware of Ultimate Autosave by ArcWolf and will save the
  game when a creature is exported via the portal if UAS is set to save when a
  creature warps out.
- Script "1 2 46 1", found in "warning icons.cos", is overwritten to add an
  additional warning message type to the creature warning icons (the ones that
  appear when a creature warps in, out, etc.) Its functionality for the existing
  types remains the same. You do not need to restore the original script after
  removing this agent, but you can if you like.

Version history
---------------
1.1
- Fixed a rare "invalid targ" error thrown by warp portals if a creature
  activates one then activates an export portal soon afterwards.

Emmental
https://github.com/chiizujin/edsa
