# Keyboard__HdnExtended_xorgLayout
Hands Down Neu layout with universal symbols for Xorg.

- `.Xkeymap.xkb` - whole layout, merged with default in `~/.xinitrc`.
- `us13` - symbols only part, used in `/etc/X11/xorg.conf.d/00-keyboard.conf` to
persist layout even when suspending session (sleep, for instance).
