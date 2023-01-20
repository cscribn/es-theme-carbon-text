# Carbon Text Theme for EmulationStation

Have you ever had trouble dicerning a system based on its logo, such as `FBNeo's "F"`? Have you wondered whether `Game Gear` should be sorted with the `Gs`, for `Game`, or the `Ss`, for `Sega`? This theme was designed to address those issues. Instead of displaying the system's controller, it instead displays the full system name. I like to use the names from the [Libretro Database](https://db.libretro.com). Also, minimal meta data is utilized. Further, some systems have been added.

![System Select](README/System%20Select.png) ![Detailed Game List](README/Detailed%20Game%20List.png)

Based on ['carbon' v2.5 - 2020-11-17 by Tomaz](https://github.com/RetroPie/es-theme-carbon-2021).

## Configuration

### Change Font

Copy your font to "art" folder.
Open "carbon/theme.xml" with a text editor and change `<themeFont>./art/Cabin-Bold.ttf</themeFont>` to the paths for your fonts. This will have the theme use your font.

### Change Color

Open "theme.xml" with a text editor and change `<themeColor>${colorRed}</themeColor>` to any of the colors listed above it.

### Change Sound

Copy your wav file to `art` folder.
Open `theme.xml` with a text editor and change `<themeScrollSound>./art/scroll.wav</themeScrollSound>` to the path to your wav file.
