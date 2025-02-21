# Space Duel Freeplay Hack
This is a free play hack for Atari's Space Duel arcade machine. 

# Features
- Works in Upright and Cocktail Mode
- Flashes "FREE PLAY" when in attract in Freeplay mode
- Full attract mode plays when on freeplay, preventing burn-in
- Flashes "start" light on Freeplay mode. Select remains unlit until menu is engaged.
- Checksums match what the machine expects and self-test passes.
- All coin modes are preserved and fully functional (accessible via dip setting)

# Instructions
- Download this repository
- Using Lunar IPS, and your own ROMS, apply each IPS patch to rom R1 and rom KL1
- Burn the ROMS (uses 2x 2532 ROMs)
- Install in the game.
- Set dip switch to "Freeplay"
- Set "per game" DIP option, instead of "per player"

# Known Issues
- This hack ONLY works with the English language DIP setting. This is because the "Free Play" message overwrote a german debugging message. Changing the language influences the value of the accumulator that governs the offset used for the coin mode message, so use in languages other than English can result in garbled text at best, or in the case of spanish, completely crashing the game. I have not considered thi sa high priority to fix, so you have been warned.

  
