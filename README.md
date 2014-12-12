== modified keyboard layout for us

This keyboard file modifies the us keyboard file to give you an additional
dvorak variant. This variant includes german umlauts with AltGr + A etc.
Additionally there are parenthesises on AltGr + E and AltGr + H, as well
as curly braces on AltGr + I and AltGr + D.

The interesting part in this file is the dvorak-de-pro variant. The file
should go to /usr/share/X11/xkb/symbols but be careful when overwriting
existing files.  Once the file is there it can be loaded with

  setxkbmap us dvorak-de-pro


