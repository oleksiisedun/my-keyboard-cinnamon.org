# Bug-free Cinnamon keyboard applet
## Based on [keyboard@cinnamon.org](https://github.com/linuxmint/cinnamon/tree/master/files/usr/share/cinnamon/applets/keyboard%40cinnamon.org)

An applet is basically a directory, whose name is the UUID, containing two files:
- A “metadata.json” file which contains information about the applet, such as its name, description, etc.
- An “applet.js” file which contains its code.

Applets go in ~/.local/share/cinnamon/applets (or in /usr/share/cinnamon/applets if you want them installed system-wide).
