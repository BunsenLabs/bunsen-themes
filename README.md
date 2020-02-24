# bunsen-themes
Bunsen Theme Collection

![Bunsenlabs Helium default theme](http://i.imgur.com/smeilkCm.jpg)

Screenshot of Bunsen, the default theme.

## Manual tweaks needed for Beam-HiDPI

Add these two lines to ``~/.Xresources`` and re-login or run ``xrdb -merge ~/.Xresources`` to activate. For ``Xft.dpi`` uncommenting and adjusting line 7 is fine, too. Just remove the leading ``!`` and replace ``96`` by ``160``.

```
Xft.dpi: 160
Xcursor.size: 48
```

These values were found giving the best results but depending on your screen's resolution ymmv. Adjust them to your preferences.
