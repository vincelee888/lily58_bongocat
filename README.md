# Lily58 BongoCat + WPM + Layer Indicator

This is a combination of the default Lily58 layout / configs / etc combined with https://github.com/jordi-7/qmk_firmware/tree/master/keyboards/lily58/keymaps/jgr

I could not get their version working, but managed to adapt the code to work.

This SHOULD compile and run with no issues assuming:

* Lily58 Pro
  * Using Arduino Pro Micro (or clone)
  * No RGB underglow
  * Left-side as master

# What it does

This keymap uses the Lily58's default layout. You could change this in `keymap.c` towards the top if desired.

This keymap adds text to the left OLED to show your current estimated WPM, as well as what layer you are on.

This keymap adds a Bongo Cat animation loop on the right OLED. It does not currently react to text/etc.