# Custom Assets

At the moment, EmuVR supports adding a few custom textures to the game to make it your own. Below are instructions on how to add these assets. Once things like dimensions and templates are available, they will be added to each section.

At the moment, we can change:

- Labels/CD Images for games
- Posters throughout the room(in preset locations)
- The wallpaper for the room
- The bedspread

# Labels
Cartridge Labels and CD Art go in your `Custom/Labels` folder, and should follow the **exact** same file structure as your Games folder.

For example, if you are adding a label for Super Mario Bros 3, which in this example is located in:

`EmuVR\Games\NES\Super Mario Bros 3\Super Mario Bros 3.nes`

You would add the label in:

`EmuVR\Custom\Labels\NES\Super Mario Bros 3\Super Mario Bros 3.jpg`

Alternatively, you can use .png files for your labels.

*TODO: Add dimensions, filetypes, and templates for each type of label*


# Posters
Posters are added in `Custom/Posters`, named as 01-27. These should be in PNG format.

Examples are also available(in the Examples folder), and it is highly recommended you copy those to your Posters folder so that you can see where each poster is located in-game.

# Wall & Bed
You can change your bed sheets, pillow, and wallpaper by changing the following files:
`Custom\Misc\wallpaper.png`
`Custom\Misc\bed_sheet.png`
`Custom\Misc\pillow.png`

Additionally, there is a .txt with each of these that you can use to set tiling options and offsets.

