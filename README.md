# InkscapeSkyFonts
Use SkyFonts Fonts in Inkscape on Windows

1. Usually the folder is in `C:\Program Files\Inkscape`

2. Go to the `\etc\fonts\conf.d` folder.

3. Open `51-local.conf` with a text editor.

4. Add the following line under the `<include ignore_missing=”yes”>local.conf</include>` line:
```xml
<dir>C:\Users\{user}\AppData\Roaming\Monotype\skyfonts-google</dir>
```

5. Save and close. Your SkyFonts Fonts are now available in Inkscape.
