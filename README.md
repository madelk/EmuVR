# EmuVR

![](/images/logo-medium.png)
1. Extract EmuVR.7z anywhere
2. Download Retroarch 1.7.5: http://buildbot.libretro.com/stable/1.7.5/windows/x86_64/RetroArch.7z
(Stay always on that version, it's better to have a clean download, try to not use your previous installation)
	1. Extract it into the EmuVR\Retroarch folder
3. Extrack this file into the same place: "Extract this here after installing Retroarch.zip"
4. Open Retroarch once, the quit, so it can create a default config file. This is important(edited)
5. Copy all your games into the Games folder
	1. Every system must have its own folder, example: PS1, GBA, SNES, SEGA GENESIS
	(They can be called anything)
	2. They can be called anything. Separated folder will distinguish their appearance and connectivity with consoles.
	For example, there should be a folder for SNES PAL and SNES NTSC, as the cartriges look different.
6. Open \EmuVR\Game Scanner\Game Scanner.exe
  1. Click "Attempt Autofill"
(This will check for common names for systems and should fill in most of your folders. Example for PS1 names to search from the database: PS1, PSX, PlayStation,	PlayStation 1, PSONE, PS ONE, PS 1, etc)
  2. Check for folders that it could not find, and add them by manually by clicking on "Add Folders..."
  3. change the Media column option to say what kind of media it is. Again based on appearence and connectivity. Example: MSX has variants for cartridges, floppies and tapes.
  4. Then just change any Media or Core option for anything, and save again. No need to rescan the games. That's a bug I got TODAY, will fix later. Without that, the games won't run. (but they should still be showing up on the list)
  5. select one of the compatible cores for your selected media in the Core section. When choosing a media type, it will select the first core, and they're kinda sorted for optimization or popularity. So the autofill should get you the best setup.
(EmuVR will first try to load the Oculus drivers, if not found, the SteamVR drivers, and if not found, desktop mode. Those shortcuts are just to force one mode or another if you want. E.g. playing in desktop mode even if you're using SteamVR.)
  6. Click "Save Changes". That will save a "emuvr_core.txt" with some settings into each of your console folders.
  7. Click "Download missing cores". See the little arrows to the left in the Cores folders? Those are cores that you still haven't downloaded. This button should download and extract them automatically in the right place on Retroarch's folders.
  8. Click "Scan Games for EmuVR". What it does is it will first use Retroarch's own scanner to find games against the database, and their "canonical" names. Then it will run another scan to check for files with the expected extensions in the correct folders for each core. Example: for SNES cores, it will look for files ending in .sfc, .smc, and it will also look inside .zip files.

# Controls
Main document [here](controls.md)
