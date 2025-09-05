rEGGulator (1.2)

The rEGGulator will attempt to maintain a desired number of Norn eggs. If there
are too few then Norns will be encouraged to breed. Too many and Norns are
discouraged from breeding.

The desired minimum and maximum numbers of eggs can be set by clicking the
number, entering a new value and pressing enter.

The rEGGulator can be turned on and off with the green button. This button
blinks every five seconds as the rEGGulator works."

Notes
-----
It's a minor point of note, but Norns are discouraged from breeding when the
number of eggs is *at* the maximum limit since we do not want to go over that
number. The rationale here is that Norns are generally inclined to reproduce and
staying under the maximum limit can be controlled by the rEGGulator, but falling
under (a Norn dying and an egg hatching) can not.

Installation
-----------
Due to the way the Agent Injector/Creator sort agents in their lists, the
rEGGulator will appear near the end of the list.

Thanks
-----
Thanks to DaveS for testing, bug-catching, and information about engine issues
relating to the urge command.

Version history
---------------
1.2
- 'urge' is no longer used to encourage Norns to breed.
1.1
- The agent no longer disappears behind the inventory when dropped into it.
- Handles being in the inventory when attempting to find the already-injected
  agent.

Emmental
https://github.com/chiizujin/edsa
