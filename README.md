# yabai enhanced Plugin for BitBar

Bitbar plugin to display yabai space ID and and mode with custom icon themes and dark mode support.

Supports switching spaces and restarting and stopping yabai.

![Screenshot of yabai enhanced plugin for BitBar](https://github.com/chrisb86/bitbar_yabai_enhanced/raw/main/screenshot.png)

## Custom themes
To use another icon theme, create a folder yabai_enhanced/{THEME_NAME} in your BitBar plugins directory and put the icon files there. Set the theme name in the script.

The Plugin looks for following files and uses them according to the dark mode state:

- bsp_dark.png
- bsp_light.png
- float_dark.png
- float_light.png
- stack_dark.png
- stack_light.png

The default theme is included in the script as base64 blobs and doesn't need PNG files.

