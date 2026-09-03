Solar Fox Freeplay (Midway)

Features
--------
- Freeplay when Coin Chute 1 # Credits = 9 (NVRAM 0x7004).
- Attract shows FREE PLAY and PRESS FIRE TO START; INSERT COINS line blanked.
- Credit counter hidden on screen during freeplay, including during gameplay.
- Boot self-test bypass (JP at 0x002D) — no hang if a ROM checksum fails.
- Freeplay selectable through location setup.
- Leaving freeplay (9 > 1–8) clears stale credit count in NVRAM.
- All other coin modes preserved

Enable freeplay
---------------
Setup menu > Game options > Coin Chute 1 # Credits > set to 9.
Label shows FREE PLAY. Setting persists in NVRAM.

Install
-------
IPS: Apply each file in ips_patches/ to the matching stock ROM

Known Issues
---------------------
- Physical coin insert may still increment the credit counter in freeplay.
