Pond Fish Food - Docking Station Update

This is an update of the Creatures 3 Pond Fish Food agent by Spirit to enable
it to be fully compatible with undocked Docking Station worlds.

Notes
-----
The intent behind this update was to allow it to be used in an undocked DS world
with the C3-in-DS Norn Terrarium injected. The agent previously moved itself to
Engineering, which does not exist with this setup.

It is allowed to inject into worlds without the Norn Terrarium because, while it
is intended to be a fish feeder, it can feed anything that decides to eat it.

Changes to Pond Fish Food
-------------------------
- The feeder is now moved to the pond if it exists, otherwise it assumes
  undocked DS and moves it to the workshop.
- The agent now has a proper name in the injector.
- There is now a catalogue file.
- The remover now also removes the script.

Credits
-------
Original agent:          Spirit
DS compatibility update: Emmental

Emmental
https://github.com/chiizujin/edsa
