DigDug Freeplay Hack

This is a series of Freeplay Hacks for Dig Dug by Namco and Atari

There are eight versions (whewlad)

They are divided into:

Atari vs. Namco
Rev1 vs. Rev2
Dip Selectable vs. Freeplay Only

Features:
- Dip Selectable (1 coin 7 credits = Free Play)*
- Free Play Text Appears on Screen in Free Play Mode
- Start Lights Flash in Free Play Mode In Attract
- Full Attract Sequence Plays
- Support for All Dig Dug ROM Revisions 


Removed Features (Gotta Make Space Somewhere):
- Ram Test
- ROM Test 

\* As in the name, "FreePlay Only" Roms ignore dip settings and always use FreePlay. (Why would you want this?)

## Dig Dug Freeplay — Output Builds

| Manufacturer | Revision | Parent ROM Set | Free Play Style | Path | Tested Status |
|---|---|---|---|---|---|
| Atari | Rev 2 | `digdugat` | DIP Select (Coin B = 1 coin / 7 credits > Freeplay) | `Atari/Atari Rev 2/Dip Selectable/` | Tested on hardware |
| Atari | Rev 2 | `digdugat` | Freeplay Only (always on) | `Atari/Atari Rev 2/Always Freeplay/` | Tested on Mame Only |
| Atari | Rev 1 | `digdugat1` | DIP Select (Coin B = 1 coin / 7 credits > Freeplay) | `Atari/Atari Rev 1/Dip Selectable/` | Tested on Mame Only |
| Atari | Rev 1 | `digdugat1` | Freeplay Only (always on) | `Atari/Atari Rev 1/Always Freeplay/` | Tested on Mame Only |
| Namco | Rev 2 | `digdug` | DIP Select (Coin B = 1 coin / 7 credits > Freeplay) | `Namco/Namco Rev 2/Dip Selectable/` | Tested on Mame Only |
| Namco | Rev 2 | `digdug` | Freeplay Only (always on) | `Namco/Namco Rev 2/Always Freeplay/` | Tested on Mame Only |
| Namco | Rev 1 | `digdug1` | DIP Select | `Namco/Namco Rev 1/Dip Selectable/` | Unsupported |
| Namco | Rev 1 | `digdug1` | Freeplay Only | `Namco/Namco Rev 1/Always Freeplay/` | Unsupported |

Paths are relative to `Dig Dug/` (this directory). Each folder contains LunarIPS patch files (`.ips`) for the parent ROM set.
