<br><br>
# BugId01

#### Screen blinks when HDR is off
Screen blinks when player got any damage frome enemies.

#### Steps to reproduce 
1. Launch the RBDoom3BFG.exe
2. Load any level from DEV menu, recommend "Alpha Labs 3" for fastest test.   
3. Open a console via Ctrl+Alt+` and type "set r_useHDR 0", then press Enter.
4. Find any enemy and get damage from it (in case with "Alpha Labs 3" just move forward.

#### Current behaviour 
The screen blinks red  when player got a damage from projectile, melee and bullets.

#### Expected behaviour 
When enemies hits a player game engine shows default damage animation.

#### Relevant logs and/or screenshots (optional)
![bug](https://i.imgur.com/KgmlF2A.png)

#### Other comment (optional)
If change shadow parameter to "set r_useSSGI 1", bug doesnt reveal.

#### Reported by
spectrln
