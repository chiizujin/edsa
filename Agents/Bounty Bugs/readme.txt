Bounty Bugs (1.3)

These little bugs wriggle around, minding their own business. They can be eaten
but if left alone long enough they may have a little surprise in store.

Thanks
------
Thanks must go to Uttar of Creature Creations (www.creations2000.net) for
testing, finding a bug (the non-crawly type) and giving me some code to fix it.
:)

Version history
---------------
1.3
- Removed all URGEs and some "bad" CHEMs/STIMs. As a result, bugs will be eaten
  much less frequently.
- Added EMITs to applicable bounties.
- Added the ability to push, pull, and hit the bugs.
- Capped the number of bugs at 10.
- Slowed down the nest's tick rate.
- Slowed down the bugs' tick rate and adjusted their movement method.
- Bugs can now try to jump over obstacles if they get stuck.
- Reduced the lifetime of bugs and increased the chance of a bounty.
- Bounties now stay around for longer.
- Bugs and bounties no longer disappear while being carried by a creature.
- Added location checks to the creation of bugs and bounties.
- Increased all permeabilities so that nothing falls through floors.
- Made minor changes to the catalogue file to reflect changes.
- Removed the ability to inject the agent into standalone Creatures 3.
1.2
- Lowered boredom reduction as it was a little overpowered.
- Fixed an "activate 2" script that was not sending its "from" value to a called
  script.
- Slightly increased bug movement speed to give them a little more hill climbing
  power.
- Added a kill script to one of the bounties so that it no longer stays around
  forever if not interacted with.
1.1
- The nest no longer falls through elevator shafts and upper level floors.
- The agent can now be injected using the C3 creator machine without causing
  errors (or killing the machine if auto-kill is enabled).

Emmental
https://github.com/chiizujin/edsa
