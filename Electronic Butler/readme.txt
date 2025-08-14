Electronic Butler (1.0)

This electronic device monitors the speech of creatures anywhere in
the world.

Any complaining of hunger or boredom are served up with the appropriate
food or a toy.  Food is created anew and toys are selected from what's
already in the world and moved near the creature.

The butler can be turned on and off by clicking it.

Note that this agent does "cheat" with CAOS by forcing the creature to
eat/play for 5 seconds.  If you don't like such agents then this
probably isn't for you. :)

General notes
-------------
This agent is by no means perfect.  Here are a few points to note:
- If more than one creature speaks simultaneously then the butler will
  not be able to service both of them.
- The butler has to keep control of creatures it is servicing for 5
  seconds.  It can cope with up to 5 at once.
- When food is created and toys are moved, the creature will not
  necessarily use the one created/moved if there are others about.
- The butler only understands English.
- DO NOT use the CAOS command line to remove the agent - always
  "remove" the agent using the injector.  Failure to do this may result
  in some creatures being stuck with an urge that will never go away.
  If you do this accidentally (or if the agent is killed for any other
  reason) then simply re-inject it then remove it properly.

Credits
-------
The idea for this agent (or at least for something very similar) was
given to me a long time ago by someone I now can't remember.  I'm
crediting it as unknown and just saying "you know who you are".

Concept:      (unknown)
CAOS:         Emmental
Sprites:      tomtschek

Emmental
https://github.com/chiizujin/edsa
