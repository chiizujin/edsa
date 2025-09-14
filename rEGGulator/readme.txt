rEGGulator (1.3)

The rEGGulator will attempt to maintain a desired number of Norn eggs. If there
are too few then Norns will be encouraged to breed. Too many and Norns are
discouraged from breeding.

The desired minimum and maximum numbers of eggs can be set by clicking the
number, entering a new value and pressing enter.

The rEGGulator can be turned on and off with the green button. This button
blinks every five seconds as the rEGGulator works."

Connectability
--------------
The rEGGulator has an input and an output port. A positive value sent to the
input port turns it on, and a zero or negative value turns it off.

Every time the rEGGulator counts the Norn eggs it sends a value to the output
port based on the number. If the number is under the minimum limit then the
deficit is output as a negative number. If the number is over the maximum limit
then the surplus is output as a positive number. If the number of eggs is within
the desired range then 0 is output.

Notes
-----
It's a minor point of note, but Norns are discouraged from breeding when the
number of eggs is *at* the maximum limit since we do not want to go over that
number. The rationale here is that Norns are generally inclined to reproduce and
staying under the maximum limit can be controlled by the rEGGulator, but falling
under (a Norn dying and an egg hatching) can not.

Installation
-----------
- If you have previously used a version of rEGGulator prior to 1.3 then you will
  need to delete the files reggulator.c16 from the game's Images folder and
  reggulator.catalogue from the Catalogue folder so that the new versions will
  be installed.
- Due to the way the Agent Injector/Creator sort agents in their lists, the
  rEGGulator will appear near the end of the list.

Thanks
-----
Thanks to DaveS for testing, bug-catching, and information about engine issues
relating to the urge command.

Version history
---------------
1.3
- Added input/output ports.
- Fixed input parts getting focus when they shouldn't.
1.2
- 'urge' is no longer used to encourage Norns to breed.
1.1
- The agent no longer disappears behind the inventory when dropped into it.
- Handles being in the inventory when attempting to find the already-injected
  agent.

Emmental
https://github.com/chiizujin/edsa
