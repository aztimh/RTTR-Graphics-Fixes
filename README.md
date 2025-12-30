RTTR Graphics Fixes

NEW GRAPHICS/OFFSET FIXES:

MAP (MAP_0_Z, MAP_1_Z, MAP_2_Z)
- fixes hammer ware graphic when dropped at flag (previously reused axe graphic)

BAB_Z
- fixes forester door offset (correct offset: 354.rle.nx-3.ny11)
- fixes storehouse door graphic (replaces open door graphic is it missed part of the building at the top can caused a chunk to vanish when door opening)

WBAB_Z.LST
- fixes forester door offset (correct offset: 354.rle.nx-3.ny12)
- fixes storehouse door graphic (replaces open door graphic is it missed part of the building at the top can caused a chunk to vanish when door opening)

WROM_Z
- fixes Roman winter brewery door offset (correct offset: 369.rle.nx-6.ny7)

charburner
- correct open door graphic for Winterworld Roman Charburner


WELL DOORS:
Only the Roman and Bab wells have an open door graphic. These provide that to the remaining 3 nations.

AFR_Z
- adds open door graphic for Nubian well
WAFR_Z.LST
- adds open door graphic for winter Nubian well
JAP_Z
- adds open door graphic for Japanese well
WJAP_Z.LST
- adds open door graphic to winter Japanese well
VIK_Z
- adds open door graphic for Viking well
WVIK_Z.LST
- adds open door graphic for winter Viking well


MODIFIED OFFICAL SPRITES
The Roman Sergeant has the wrong crest (plumes on the helmet) when moving East or North-East. I took the correct ones (from General) and modified them to fit the sergeant. These are the sprites between: 955 and 1002

The Metalworker has many wrong sprites when carrying out tools. Most times the unique metalworker head (facial hair) is erroneously replaced with the standard carrier head. The graphics for carrying out the bow are entirely wrong as it is an empty bucket (which seems to be an abandoned tool/ware) and the armorer has graphics for carrying out bows (so at some point bows were from the Armory instead presumably).
I have modified and created metalworker sprites that provide a consistent worker model and the correct tools. They are spites between: 2198 and 2293

JOBS.BOB
- fixes roman sergeant graphics (helmet when moving right/up right)
- fixes metalworker sprites for carrying out tools (sometimes changes to generic carrier head) also fixes when carrying out bow he actually has a bow instead of empty bucket now.


PALM TREES IN GREENLAND
For some reason the order they placed the sprites for palm trees being felled are reversed. So when you chop one it is the other kind that appears to fall. There are also unused small growing palm trees that appear in the sprites before these. These are unmodified graphics but this can probably be fixed in the programming. Sprites 256-259 and 271-274 should be reversed. Also shadows: 406-409 and 421-424 should be reversed.

MAP_0_Z.LST
- fixes palm trees falling after chopped animation/shadows. They are reversed.














