# Toubleshooting
* "I can't see any consoles or carts"
   * Check EmuVR\Game Scanner\emuvr_playlist.txt . There should be no blank lines (including the top and bottom lines). If there are, delete them and try again. You will need to double check this every tim eyou scan for games.
* "My game cartridge loads in fine, but when I try to start I get a blue screen on the TV"
   * Within any console folder within the Games directory, check the "emuvr_core.txt" file for the appearance of "1". Where present, this is an error. Open the Game Scanner, change any setting, then click "Save" and close the scanner. Check the emuvr_core.txt again, and if "1" is no longer present, start EmuVR and see if your content is available.
   * If that doesn't resolve the issue, make sure to follow step 6 [here](installation.md).
* "I can't insert carts into a console"
  * The consoles that spawn initially are "Generic". They will boot the cart they spawned with, but won't accept others. Delete the initial console, spawn a desired one, and try again with the cart you wanted to play.
* "Jeepers this game is running fast!"
   * Try hitting spacebar. That's the default hotkey for fast-forward (toggle).
* (In general) "My Game won't start, and I've tried all the other steps"
   * Make sure you can run the game directly from EmuVR\Retroarch\retroarch.exe . If it doesn't run in Retroarch, it's not going to run in EmuVR. There are several causes of these kinds of issues, like missing or misnamed BIOS files. Some of the issues are even core-specific. The Retroarch documentation and help community will almost certainly be a better (or faster) resource than the EmuVR help channels (since they already have practice supporting Retroarch).
* "EmuVR is slow, stutters, or crashes"
  * EmuVR loads labels for all of the roms in the EmuVR\Games directories at runtime. Too many romes (and thus, too many labels) is known to cause performance issues and crashing. Reducing the number of roms in EmuVR\Games is recommended. There is no known upper limit, but "hundreds" is a good rule of thumb.

# Known issues

These are issues that EmuVR is aware of and will be looking into;

* Videos occasionally crash EmuVR
* There's a white ring around the view
* Gamecube games, while working in retroarch directly, aren't working in EmuVR
* Attempting to spawn a tiny(90s) screen actually spawns a medium(90s) screen
* When adding a custom texture for the pillow, it doesn't override the default one
* Occasionally, a new user's Retroarch will be set to mute by default (first time setup only)
* Consoles that spawn with the room at startup are labelled as "Generic" and won't accept cartridges. Players need to manually spawn the system of their choosing for the time being. EmuVR has stated this will be fixed in the next update.
* If you have a Videos folder defined with no media type or core, you can't save
   * ![](/images/videos_unselected_error.png)

# Not well tested issues

These are issues that aren't well tested, and may be user specific

* Turning on a console may result in it turning off a few seconds later.
