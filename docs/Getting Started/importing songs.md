---
sidebar_position: 2
title: Importing Songs
description: Importing Songs
---

When you create a new level, you’ll want to select `Gameplay > Play` song in the event palette before placing the event on your timeline.

Remember to <u>set your BPM</u>!

To find the BPM of your song, it is suggested to use a BPM tapper. Good BPM tappers include:
- https://all8.com/tools/bpm.htm
- https://flat9.glitch.me/

**Try to avoid using a search engine to find the BPM, they often give inaccurate results!**

.ogg files are <u>heavily preferred</u> for Play song events, but .wav files are usable. **MP3 files are no longer usable.**

Offset can either be adjusted in the editor, or manually by cutting the song in a separate program (e.g. Audacity).

**[IMAGE]**

Opening the level properties panel [Ctrl + I] allows you to add and edit basic level info that appears on the song select screen.

**[IMAGE]**

Below the METADATA section are the Variant Specific,  BG and OTHER sections, which let you choose a song select background image* and miscellaneous properties.

**[IMAGE]**

*BG images must fit the eight-channel palette, which is explained further in the decorations guide.

# Issues with Importing Songs

Can’t get your song imported? You’ve come to the right place.

Some things to check:
- Is your file in a supported format? (Hint: if it’s an MP3, those are not supported!)
  - Ok, but is it actually in a supported format?
    - Many converters and downloaders can give broken files that are actually other formats in disguise!
    - For downloading, https://cobalt.tools/ is known to work.
    - For converting, you can use https://www.audacityteam.org/
  - Do you have file extensions turned on?
    - If you don’t, here is a tutorial: https://www.howtogeek.com/205086/beginner-how-to-make-windows-show-file-extensions
  - Now that you have file extensions turned on, does your file only have one extension?
    - If your file is named “song.ogg.ogg” or something similar, you need to change it to just be “song.ogg”
  - Is your file named properly, and is the file set to that name in your play song event?
    - In the play song event, you need to put the file name, including the extension. 
  - Have you set your BPM and offset correctly?
    - If you are having trouble finding the BPM of your song, please ask in the discord. **Starting your level with the wrong BPM will make your level out of sync and bad to play, and there is no way to fix it other than starting the level over, so please make sure you have it correct!!**

