0. Credits and Usage

The original Norn Statistics and Medical Monitor were created by Emmental, whose original site has gone down but whose contributions to the community are still valued today. These updates were done out of gratitude for all the times their agents have helped me in my games, to the point where I can't play without them now.

This edit was done by SunlitMiracle, and is free to be reuploaded elsewhere and altered further for both personal and public use.

Updated as of December 29th 2024.

1. Installation

- Place "Medical Monitor Update.agents" and "Norn Stats Update.agents" in your "Docking Station/My Agents" installation folder. If you have Emmental's original versions or my previous versions in, removing them is recommended to avoid confusion and errors.

- IF YOU'VE USED PREVIOUS VERSIONS (either Emmental's or mine), you will also need to copy the contents of Catalogue and Images into your respective folders. You may also need to do this in your Creatures 3 subfolder if anything has previously been extracted there. The updated catalogue files add further explanations and some tooltips, and the updated "norn stats 2.c16" has edited or updated buttons that are required for usage.

- OPTIONAL BUT HIGHLY RECOMMENDED: Download the Unofficial Chemicals Catalogue https://eemfoo.org/archive/downloads/bb16 and Short Chem Names https://eemfoo.org/archive/downloads/7412 to ensure chemicals are displayed properly. Even if you don't use unofficial creatures with fan-created chemicals, this is recommended due to Chemical 90, Wounded, not being named in the game's catalogue files for some reason. Install in both the Docking Station/Catalogue and the Creatures 3/Catalogue folders. The monitors are still functional without this but several chemicals will show up as only numbers.

2. Features

These updates are intended to better track the many ailments that can afflict a Creature, as well as accomodate more playstyles that use fan-made content such as True Warmbloods and Nornbinary.

Changes to both agents:
- Truncation of names over 16 characters so that they don't overlap the right-side text.
- Changed (D) to Dead, placed it either in health problems (MM) or next to the Pregnancy label (NS) for better visibility.
- Tracking of Grendels, Ettins, and Geats enabled by default.

Changes to Medical Monitor:
- Added Pregnancy check
- Added checks for high values of Wounded, the three Hungers, Coldness, Hotness, Tryptamine, Body Heat (TWB only)
- Added checks for low values of Glycogen, Oxygen, Water, ATP, Body Heat (TWB only), and Oxygenated Hemoglobin (TWB only)

Changes to Norn Statistics:
- Changed O/T/A button text to say WARN, due to the addition of another immortality check.
- Dead label is now listed next to the Pregnant label
- Added an immortality check for "zombies", shortened to "Z", to alert the player of any creatures who are alive but have ATP or Energy under 1 (which is far below most genomes' death threshold)
- The Toxins immortality check also now includes Grendels, will exclude dead creatures, and only tracks specific chemicals (Cyanide, Belladonna, ATP Decoupler, and Wounded) to reduce possible false positives. Detection threshold lowered to 90.
- Re-enabled tracking of creatures that are neither male nor female; changed descriptors from "Unknown" to "Nonbinary" and from "?" to "X". While they are always included in the main panel and in the immortality/fast-ager checks, due to readability issues with long text in the population tracker (particularly with large populations and high generations) they do not appear by default. The NB button will toggle them back on.
- Added tracking of the "Dead" lifestage, here renamed "Max. Age" in order to avoid confusion with death in general.

3. Known Issues

- Both: Neither agent is fully compatible with Toxic breeds and will generate lots of false positives regarding toxins. I've thought of making toxic-friendly versions, but since toxic breeds have their own unique quirks (such as whether or not they *need* to have toxins in order to live) I don't know if a single version for all of them is possible.

- Both: If a creature is given a name with many wide characters, like WWWWWWWWWWWWWWWW, their name may still overlap other text even if truncated.

- MM: Some checks are sensitive, such as Glycogen and every toxin, antigen, and wounded. This can result in creatures lingering in your alerts even though they aren't in any danger.

- MM: The TWB/TCB conditional checks conflict with Grendels of Minimordor, who also use Chemical 110. It's not a huge issue since GoMs are supposed to instantly die with 110, but MM will falsely flag their corpses as having TWB-specific issues like no blood.

- NS: If you have a high generation number and/or a lot of creatures, the population count may run off the edge of the agent box. This was possible with the original version too and can still happen in extreme cases.

- NS: The check for low ATP and Energy may result in false positives if a creature somehow reaches a critically low state without immediately dying and the agent makes a check between those times. Similarly, a mortal creature who manages to accumulate multiple deadly chemicals at once without immediately dying may also be falsely flagged. The alert will clear on its own after the creature either recovers or dies.

- NS: Creatures with custom-tailored lifespans may trigger the old age immortality warning or the fast-ager warning. Unlike the above, this will not clear out unless either the alert is disabled, the creature's species is disabled, or the creature themself is removed from the world.

4. Changelog

Medical Monitor v1.4.1 (retroactively named)

Medical Monitor v1.4.2

Norn Statistics v1.2.1 (retroactively named)

- First release of SunlitMiracle's updates. Most features listed above were added, but the "Dead" lifestage was called "Decrepit" and all chemicals 66-90 were used in the toxin immortality check.

Norn Statistics v1.2.2

- "Decrepit" renamed to "Max. Age" for clarity.
- NB button added to mitigate issues with long text with the population counter.
- Most chemicals removed from toxin immortality check, as even at high levels they would linger on extremely sick but not immortal creatures, resulting in false positives.
- ATP and Energy check adjust to hopefully reduce false positives.
- Catalogue updated with more information in the help file and with tooltips for various buttons.
