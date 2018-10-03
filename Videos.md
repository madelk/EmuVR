To play videos;

1. Create a folder called "Videos" in the EmuVR Games folder ("EmuVR\Games\Videos")
2. Create a file called "emuvr_core.txt" with the following content;

```
core = "video"
media = "Video"
```

3. Place video files within that folder.
4. Run the game scanner, add a new directory (the video directory) and leave the type and core blank.
5. Edit EmuVR\Game Scanner\user_custom_playlist.txt with 3-line blocks as shown below (no empty lines in the file);

```
Games\Videos\video_file_name.mp4
My Video Title
anything|anything
```
6. Play it (instructions pending...)
