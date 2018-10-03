# Toubleshooting
* "I can't see any consoles or carts"
   * Check EmuVR\Game Scanner\emuvr_playlist.txt . There should be no blank lines (including the top and bottom lines). If there are, delete them and try again. You will need to double check this every tim eyou scan for games.
* "My game cartridge loads in fine, but when I try to start I get a blue screen on the TV"
   * Within any console folder within the Games directory, check the "emuvr_core.txt" file for the appearance of "1". Where present, this is an error. Open the Game Scanner, change any setting, then click "Save" and close the scanner. Check the emuvr_core.txt again, and if "1" is no longer present, start EmuVR and see if your content is available.

# Known issues

These are issues that EmuVR is aware of and will be looking into;

* Videos occasionally crash EmuVR
* There's a white ring around the view
