# dmxcontrol-hsp3
dmxcontrol-hsp3 is the some hsp3 applications and modules to control DMX parameters using Arduino Bridge for DMX Shield (ABDS). 

## Files
* DMX main library, send data for ABDS through COM [dmxbridge.hsp](./dmxbridge.hsp)
* Commandline DMX tester [dmxtest.hsp](./dmxtest.hsp)
* DMX light pattern sequencer [firstLF.hsp](./firstLF.hsp)
* User functions for typical sets of stage lights [keionlight.hsp](./keionlight.hsp)
* Realtime light activator driven with space key [rescuesignal.hsp](./rescuesignal.hsp)
* The imitation of the awaiting animation of Japanese vending machines [zihanki.hsp](./zihanki.hsp)

## How to build pattern sequencer
1. Download and install HSP3 (HSP 3.6 is recommended)
2. Open `firstLF.hsp` with HSPスクリプトエディタ.
3. Copy `hspext.dll` from the HSP3.6's directory (`C:\HSP36` by default) to the directory contains `firstLF.hsp`
4. Press Ctrl + F9 in HSPスクリプトエディタ. This process creates `firstLF.exe` in the same folder.
5. Run `firstLF.exe`.