Mods for Onion V4.3.1-1 for Mini V4 with RTC
- Resolution fix (Commit aa329ba on OnionUI main branch)
- Disable Emulated time skip as it is not needed with the newer Mini V4 with RTC.
- Enable blue light schedule function to automatically turn on/off blue light filter on startup.

Turn on blue light schedule: 
1. Rename ".blf_" in .tmp_update/config to ".blf".
2. Configure schedule by changing the time in files "blueLightTime" and "blueLightTimeOff" in .tmp_update/config/display.

Notes:
- Set correct time in Apps -> Clock.
- Schedule only works for Miyoo Mini V4 with RTC.
