Ainarda agents (1.1)

Ainarda is a fantastic metaroom created by Merboy that never received a
completed release. The available downloads consist of the empty metaroom, a
zip file of various agents without any installers, and a vine sprite set.

This agent populates the metaroom with those agents, as well as doing a few
other things, so that Ainarda can more easily be used as originally intended (or
at least as near as I could get based on what's in the agent zip file.)

What's included from Merboy
---------------------------
- Elevators and a gondola to get around.
- Several fruits and seeds.
- Foreground overlays.
- Ambient animations.
- Some secret stuff.

Additional changes
------------------
- A Norn Home has been added in the upper left room of the treehouse.
- Added some additional foreground overlays in the treehouse.
- The permiability of the floors in the treehouse has been lowered slightly to
  lessen cases where things fall through the floor.
- The lower level of the maison (the four-level building at the right of the
  metaroom) now serves as an incubator, similar to the heatpan in Docking
  Station).
- Elevators no longer use the highest need to determine whether to go up or down
  and only grab the creature that pushes/pulls it.
- Cabin sizes have been increased to allow grendels and Rorschach norns to fit.
- CA links and intermediate rooms have been added to support the elevators.
- Pomleys (the purple fruit) have been moved to a different tree as they were
  originally falling in an inaccessible area (in a room but without a means of
  getting there.)
- Added sound to the gondola and to something else I can't mention (that secret
  stuff).
- Implemented the castle dark grapes as per the description on Merboy's site.
- If Creatures 3 is installed, the water areas are populated using C3 assets.
  There is no ecosystem added; this is mainly just for decoration, although fish
  can be eaten. The world does not need to be docked for this to work.
- Added a catalogue file with entries for all of the agents.
- Created a remover to remove the agents and the metaroom.

Installation
------------
1. Inject "Ainarda". This can be found as "Ainarda World" at
   https://eem.foo/archive/downloads/5726-ainarda-world-zip This injects the
   empty metaroom and adds the favourite place icon.
   Note that this will take several seconds to inject, during which time the
   game will appear to have frozen. When it has finished you will be taken to
   the metaroom.
2. Inject "Ainarda agents" (this) to do everything else.

Note that you do not require the separate zip file of Merboy's agents. For
reference, it can be found at
https://eem.foo/archive/downloads/52c7-agents-for-ainarda-world-zip

Removal
-------
A separate remover agent is included which removes all agents in Ainarda, all
Ainarda scripts, and the metaroom itself. Creatures, eggs, portable portals, and
workshop teleporters are moved back to the appropriate Docking Station areas but
everything else is removed.

Inject "Ainarda (Remove)" to use it.

Notes
-----
- An important requirement I'd placed on myself was to do this without altering
  the base metaroom installation; it would be a supplement to it.
- I tried to tried keep things mostly as they were in the original scripts but
  there were some parts where I wasn't sure what the original intention was.
  There were also a few bug fixes and adjustments along the way.
- There is no way in and out of the metaroom so I recommend using portals such
  as Mugendai's Interporter or Risen Angel's Offline Warp Portals. You could
  also use the Docking Station workshop portals.
- Most of the food sources available are fruit - two on the surface, one
  underground, and one in the castle. The only other food is the blossoms
  (seeds) from the trees in the lower left. You will, most likely, need to add
  additional food sources provided by your choice of agents. Mea's various
  mushroom and radish vendor agents fit well here.
- The metaroom will still seem quite empty after installation but there are
  hundreds of agents out there to make the metaroom into whatever you want.
- The metaroom was originally intended to be released for Creatures 2 so it was
  designed to wrap around at the left and right edges. I have not added this
  functionality as the implementation of this is quite hacky and is beyond the
  scope of what I wanted to achieve.
- More information about Ainara and its original vision can be found on Merboy's
  site at https://www.thelanternlight.com/download.html. The metaroom, separate
  agent downloads, and the vine sprites can also be found there.

Credits and thanks
------------------
- First and foremost, credit goes to Merboy for the original creation.
- Additionally, here is a quote from Merboy, taken from
  https://www.thelanternlight.com/download.html:
    "I would very much like to thank Ghosthande, Laura, Moe, Liam, and AquaShee
    for their absolutely gracious help. Without their expertise and selflessness
    Ainarda would not have been even slightly possible. A huge thank you to each
    of them."
- Thanks to Risen Angel and SpaceSR for help with the CA stuff.
- Thanks to Risen Angel for bug-finding.
- Thanks to Doringo for some room-wrapping information.
- I would also like to thank my group of norns and Alba the grendel for their
  help and patience during testing.
- Additional sounds came from Freesound (https://freesound.org/):
   - https://freesound.org/people/EpicWizard/sounds/316595/ by EpicWizard
   - https://freesound.org/people/klankbeeld/sounds/238900/ by klankbeeld
   - https://freesound.org/people/joedeshon/sounds/339184/ by joedeshon

Version history
---------------
1.1
- Fixed missing ainarda_incubator.c16 file.
- Fixed incorrect classification of marine plants and vents.
