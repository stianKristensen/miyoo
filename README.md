Mods for Onion V4.3.1-1 for Mini V4 with RTC
- Resolution fix ([Commit aa329ba](https://github.com/OnionUI/Onion/commit/aa329bac862a93e12839c1a46765cdc270a3e448) on OnionUI main branch)
- Disable Emulated time skip as it is not needed with the newer Mini V4 with RTC.
- Enable blue light schedule function to automatically turn on/off blue light filter on startup.

Installation:
- Drag .tmp_update folder to SD root, overwrite files when prompted.

Enable blue light schedule: 
1. Rename ".blf_" in .tmp_update/config to ".blf".
2. Configure schedule by changing the time in files "blueLightTime" and "blueLightTimeOff" in .tmp_update/config/display.
3. Ensure correct time in Apps -> Clock.

HOW TO CHECK IF YOUR MINI V4 HAS RTC:
1. Drag the .noTimeRestore file to .tmp_update/config (this will disable the default emulated time skip of +4 hours every time the device is turned on).
2. Turn on device and go to Apps -> Clock.
3. Set the time and confirm by pressing START.
4. Turn off device, then wait a few seconds.
5. Turn on device and check the clock app again. You have RTC if the time shown is still correct (meaning time has passed correctly while the device was switched off).

