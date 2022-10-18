# mpv-modern-x-compact
Compact version of modern-x osc for mpv with a neat web-player type UI

![preview](https://raw.githubusercontent.com/1-minute-to-midnight/mpv-morden-x-compact/main/preview.png)

# How to install
Put the .lua file into "~~/scripts/" folder, and remove other osc scripts.

Set the following setting in mpv.conf :

`osc=no`

:warning: **Important**: Install dexeonify's custom-made icon font ![modernx-osc-icon.ttf](https://github.com/1-minute-to-midnight/mpv-morden-x-compact/raw/main/modernx-osc-icon.ttf) for the OSC icons or create a folder folder named fonts in the mpv config folder and drop the ttf file in there.

# Configuration
You can change various options like accent color by editing osc.conf which should be put in the "~~/scripts-opts/" folder. The usage/creation of this file is optional if you want to use the config as is.
```
# Accent of the OSC and the title bar
osc_color=000000

# Color of the seekbar progress and handle
seekbarfg_color=E39C42

# Color of the remaining seekbar
seekbarbg_color=FFFFFF
```
If you want to change the height of the seekbar or want to change the positions of various elements:
By line 1675 you will see various titles indicating each element (Seekbar, Title, Playback control buttons etc.). To move the elements horizontally (along x-axis), add or subtract values to refX or x values. Similar process can be done for y values to move it vertically (along y-axis).

## Thumbnail Support
For thumbnail support drop the thumbnail .lua files into the scripts folder
 
# Fonts
- ![Manrope](https://github.com/sharanda/manrope)

(Change osd-font in "~~mpv.conf" to get like it is in the screenshot)

# Credits
- ![Dexeonify's Personal Config](https://github.com/dexeonify/mpv-config)

- ![Maoiscat's Modern Layout](https://github.com/maoiscat/mpv-osc-morden)
