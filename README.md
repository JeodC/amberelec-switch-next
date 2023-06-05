# AmberELEC Switch Next
Imports the Switch system view from AmberELEC-Switch into Art Book Next.

## Installation
Use sftp to copy to ``` /storage/.config/emulationstation/themes``` or use file explorer to copy to ``` \\[DeviceIP]\config\emulationstation\themes```

## Feature Details
At the moment the theme has been personalized to my own liking. It works well with the following settings:

```bash
Gamelist View Style -> Video
Aspect Ratio -> 3:2
Gamelist View Style -> Metadata Off
```

Metadata such as descriptions, ratings, release year etc do work, but the battery and wifi icons overlap the boxart. I may or may not fix this later.

## Potential Issues
The system logos each use a .svg file where the size and position are governed in theme.xml, lines 80 and 81. These are hardset to a 3:2 aspect ratio and need adjustment for larger displays. Unfortunately when I initially ported the Switch system view it somehow broke some automatic alignment, and I haven't figured out how to fix it properly.

## Contributing
Pull requests welcome. Themes are simple XML files that are, for the most part, thoroughly commented.
