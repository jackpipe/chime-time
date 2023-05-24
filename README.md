# chime-time

Bash scripts for linux and macos to chime on the hour.

The chime will only play if no other audio is playing. The script also briefly listens to the sound level, and then plays ther chimes at that volume.

Currently the script try to play files named `chime-$(hr)` eg `chime-07` but it's easy enough to change to play a single chime the required number of times.
