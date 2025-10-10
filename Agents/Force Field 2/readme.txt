Selective Force Field II (1.0)

This force field can be configured to either prevent (blacklist) or only allow
(whitelist) certain types of creatures from passing, based on genus and life
stage.

For example, it could be set up to only allow Norns older than Youth to pass or
prevent Ettins older than Child from passing.

Any creatures that try to pass, but are not allowed to, are pushed back away
from the force field (non-harmfully).

To turn the force field on and off click the green button on the base.

Configuring
-----------
To configure the force field click the blue button on the base to open the
configuration panel. A combination of options can be set by using the green
arrows. Click the blue button again to close the panel. The force field can be
configured while turned on or off and changes take effect immediately.

The force field will not operate while carried by the hand or a vehicle.

Connectability
--------------
The force field has an output port and an input port on its base.

The output port outputs the genus number of the creature when one is pushed
back. The number is positive if the creature is on the right of the portal and
negative if it's on the left. For example, a Norn on the right would output 1
and an Ettin on the left would output -3.

The input port can be used to turn the force field on and off. A positive input
will turn it on and a zero or a negative input will turn it off.

Notes
-----
It's easier to pick up the portal by the base rather than the light beam. This
is because half of the beam is transparent pixels which cannot be used to grab
an agent.

Credits
-------
Some of the new graphics were given to me a long time ago and, unfortunately, I
no longer remember who they were from. It was probably one of my previous
collaborators (i.e. Data, Random, Sentinal, or tomtschek.) It could also have
been someone else entirely, but thanks must go to whomever it was.

Emmental
https://github.com/chiizujin/edsa
