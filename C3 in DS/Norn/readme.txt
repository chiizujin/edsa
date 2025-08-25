C3 in DS: Norn Terrarium (1.1)

After unzipping the agents into the "My Agents" folder and starting DS you will
have two more agents listed in your injector.

One is "Norn Terrarium" and the other is "Norn Terrarium (Remove)". I hope it's
pretty obvious what these do :)

Injecting
---------
Before you inject anything just check the following list:
- Do not attempt to inject this into a standalone C3 world
- Do not attempt to inject this into a docked C3/DS world
- Do not attempt to inject this if C3 is not installed

Basically, this is for undocked DS worlds only, but you must have C3 installed.

The room takes a couple of seconds to inject and once it has you will be taken
to the new meta-room. You will also notice a pair of teleporters that link
between the terrarium and the Docking Station. These can be moved to anywhere
you want. The existing doorways and Ettin accessways are no longer operational.

Removing
--------
To remove the meta-room you actually inject the (Remove) agent. Using the
injector's remove button on the installer agent will have no effect.

When you remove the meta-room any creatures and eggs in the meta-room are
teleported to the heat pan in the DS meso. Again, removal takes a couple of
seconds.

General notes
-------------
- It's probably a good idea to save the world before injecting or removing the
  meta-room by pressing CTRL+R. Then if anything does go wrong you can quit the
  game without saving by pressing CTRL-Break.

- If you hear a "buzz" noise when a creature tries to use a teleporter or when
  the hand tries to use it then that means a valid location could not be found
  at the other end - try moving the other teleporter away from walls or low
  roofs.

Disclaimer (stuff that has to be said)
--------------------------------------
Bear in mind that the C3 meta-rooms and agents were not really meant to be used
in this way, especially removing them, so there is always a chance that this
could break your world.

USE AT YOUR OWN RISK.

Credits
-------
Concept & new CAOS:      Emmental
New teleporter sprites:  Data

Original sprites & CAOS: Creature Labs

Beta testing:            Random
                         BarbaraNorn
                         Helen

Thanks
------
- Thanks to Frimlin for allowing his brains to be picked regarding the C3
  meta-rooms and agents.

Version history
---------------
1.1
- Fixed script error when selecting certain Norns in the egg layer.
- The favourite place icon is now removed gracefully without removing all of the
  others.
- Removing the meta-room no longer breaks some of the game's functionality.
- Bioenergy now increases (as intended).
- Added chopper toy.

Emmental
https://github.com/chiizujin/edsa
