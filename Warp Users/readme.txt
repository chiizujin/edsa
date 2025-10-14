Warp users (1.1)

A ticker that displays the names of recently-seen warp users.

The ticker can be picked up by the hand and placed elsewhere if you like.

Implementation notes
--------------------
Since there is no way to retrieve a full list of online users, this agent works
by asking the server for a random online user once every minute and builds up a
list of up to ten users that it has seen.

Every five minutes it checks its list of users so see if they are still online
and removes any that are not.

This means that the list is only a guess at who is "probably online" and doesn't
guarantee that every online user is listed, nor that they are still actually
online. However, as the warp user count is usually in the single digits, it
should be able to discover most, if not all, of the users.

This is why I'm using the term "recently-seen warp users" rather than "online
warp users".

Note that is does not take into account users sending and receiving creatures or
any of the message and chat functions. Since these are generally low-frequency
events there is a good chance that the ticker already knows about the user
before any of these happen.

Updating to version 1.1
-----------------------
If you have used a version prior to 1.1 then you will need to remove the agent
in-game BEFORE copying the new agent file into the My Agents folder. Because the
agent classifier has changed, version 1.1 will not remove previous versions.

Version history
---------------
1.1
- If you issue a 'whois <your username>' to !System, calls to 'net: ruso' will
  subsequently also be able to return your user ID. This was confirmed as a bug
  by Ketesi on Discord, but is now handled anyway (i.e. ignored.) as it is
  possible to configure the warp server to return your own user ID with 'net:
  ruso' (though not dependent on 'whois') by setting excludeSelfRUSO
  appropriately.
- Changed agent classifier.

Emmental
https://github.com/chiizujin/edsa
