![image](https://github.com/tbeaulieu/Danver/assets/3193399/a177c1e4-a5d5-4bdd-a920-d01465c2d859)

# Danver
 QML dashboard for the GARW unit, based upon the Ridge Racer 6/7 Danver Tachometer

 Contains a custom made font (Greddy Segment), based upon the Greddy Sirius Unify. All rights reserved. :) 

Change the two `width:` lines of `rpm_action` in DanverDisplay.qml (marked Chunk-style / Percentage-style) for chunky vs smooth RPM behavior. Make sure you don't have both there at the same time, or it'll bomb your dash.

Oil temperature and oil pressure are optional: turn each one on with its Show row in the settings menu. Coolant and oil temp High limits are in Celsius and the oil pressure Low limit is in bar; 0 turns a warning off.

Settings are saved as JSON in `/opt/IC7/screen_configs/Danver_config.json`. An existing `Danver_config.txt` is imported once on first run.

Check out our discord here:  https://discord.gg/bmKFrt8XP6 if you need help on installation or have any comments.
