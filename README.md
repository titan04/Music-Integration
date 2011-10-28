## Music Integration Extension

Integrate your music with the Gnome Shell.

This extension listens to Dbus MPRIS and automatically looks for players.<br/>
It automatically adds an icon to the Gnome panel when it finds a music player; you have access to basic controls there.<br/>
It will also notify you when the song changes, and you can also control the player through the notifications and message tray.<br/>
Either option is configurable.

### Installation:

1. Download and extract.
2. Put the folder `music-integration@brianrobles204` in `~/.local/share/gnome-shell/extensions/`
3. As root, put `org.gnome.shell.extensions.musicintegration.gschema.xml` in `/usr/share/glib-2.0/schemas/`
4. As root, in terminal, run: `# glib-compile-schemas /usr/share/glib-2.0/schemas/`
5. Restart the shell (Alt+F2, enter r, press enter) or log out and in.
6. Using Gnome Tweak Tool, enable the extension. `# gnome-tweak-tool`

### Authors
Made by Brian Robles (brianrobles204@gmail.com) <br/>
This extension is a fork of Jean-Philippe Braun's extension (eon@patapon.info)<br/>
Original: https://github.com/eonpatapon/gnome-shell-extensions-mediaplayer<br/>
