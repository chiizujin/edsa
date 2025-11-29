Norn Statistics (1.3)

Preamble
--------
Norn Statistics received an update for the CCSF in 2024 by SunlitMiracle, which
was distributed as a separate version. I have since fixed an old bug
(originating in the original version) in both versions and therefore, as of
version 1.3, both the original version (hereafter referred to as "Legacy") and
SunlitMiracle's version (hereafter referred to as "Update") are included in one
download.

See the file "SunlitMiracle's MM and NS updates.txt" for full details of the
changes made by SunlitMiracle.

Agent information
-----------------
This agent adds a panel to the left of the screen that displays various
information about your creatures, including their age, life stage, generation,
and if they have been through the warp. The information is updated about every
15 seconds.

It also checks for possible immortal and fast-aging creatures by checking 4
indicators:

1. Norns older than 9 hours may be immortal.
2. Norns with 2 or more toxins in their body over 95 may be immortal.
3. Norns that reached adult before they were 30 minutes old are probably
   fast-agers.
4. Norns with very low levels of energy or ATP may be immortal (Update only).

If any of these checks are matched then a "boing" sound will be heard and 1 or
more letters will appear in square brackets along with the rest of the
information for that creature:

O = Old
T = Toxins (not checked for Grendels in Legacy)
A = Aging
Z = Zombie (Energy/ATP)

This checking can be turned on or off with the O/T/A (in Legacy) or WARN (in
Update) button.

The top four buttons are used to toggle on or off the display of the various
species and the two arrow buttons are used to scroll the window if there is more
than one page of text.

The text at the bottom of the panel show the number of male, number of female
and highest generation of each species. The NB button (Update only) allows
Nornbinary creatures to be included in these counts.

Installation
------------
If you have used any version (of either agent) prior to 1.2.2:
  - Copy "norn stats 2.c16" to the game's "Images" folder.
  - Copy "norn stats.catalogue" to the game's "Catalogue" folder.

Known issues (SunlitMiracle)
----------------------------
- False positives on the immortality/aging checks can occur due to Toxic breeds'
  specialized needs, due to fanmade breeds having custom lifespans and chemical
  resistances, due to use of codes or agents to artificially age a creature, or
  even just a extremely unfortunately creature accumulating multiple illnesses
  at once. Norn Statistics cannot determine the context these suspicious event
  occur in and it's up to the player to verify if the creature in question is
  truly immortal or fast-aging.
- There's potential overlap in the population counter if there are dozens or
  hundreds of creatures or if their generation count is in the third or higher
  digits. This will become much more visible if the Nornbinary toggle is on,
  even with the abbreviated species names.

Credits and thanks
------------------
- Thanks to Random (http://members.home.net/dockingstation/) for the suggestion
  for this agent.
- Original agent: Emmental.
- Update versions 1.2.1 & 1.2.2: SunlitMiracle.

Version history (Both versions)
-------------------------------
1.3
- Fixed operation of shortcut key (CTRL+5).
- Changed CALL to MESG WRIT.

Version history (Update by SunlitMiracle)
-----------------------------------------
1.2.2
- Added Nornbinary toggle to make the population count readable again.
- Renamed "Decrepit" to "Max. Age" for better accuracy.
- Hopefully fixed the false positives on the ATP/Energy check? Lowered the
  threshold and added a second death check.
- Narrowed down the toxin check to Cyanide, Belladonna, ATP Decoupler, and
  Wounded as these are very dangerous chemicals to keep at high levels and can
  kill most creatures within seconds or even instantly; hopefully this will
  reduce false positives.
- Updated the in-game help file with new information, also added tooltips.
1.2.1
- Moved and renamed (D) marker to another line.
- Non-Norns tracked by default.
- Added immortality check for low ATP and Energy, hereby known as "Z" for
  Zombie.
- Added Wounded to immortality check for toxins and removed the Grendel
  exclusion.
- Changed Unknown/? to Nonbinary/X and enabled them to be included in the
  population count, but I'm open for feedback on the terminology.
- Added indicator for Dead lifestage (death of old age), named it "Decrepit" to
  avoid confusion with general death.

Version history (Legacy)
------------------------
1.2
- The display now updates straight away when injected, rather than waiting for
  the first timed check.
- Added fast ager/immortal checking. This can be toggled on and off.
- Added support for Ettins, Grendels and Geats. The display of any of these (as
  well as Norns) can be toggled on and off individually.
- Added counters to the bottom of the panel. These count the number of male and
  female of each species as well as showing the highest generation.
- The agent can now be injected using the C3 creator machine without causing
  errors (or killing the machine if auto-kill is enabled).
1.1
- The "youth" stage was missed out of the life stages, so stages after
  "adolescent" would incorrectly report as one greater than they actually were.

Emmental
https://github.com/chiizujin/edsa
