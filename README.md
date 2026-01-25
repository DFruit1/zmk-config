# zmk-config
ZMK keyboard config for 5-column corne keyboard. Based loosely on miryoku layout but extended in order to optimise for a wide variety of tasks such as:

- Standard typing using the Colemak keyboard layout, with most used symbols and letters on the home row.
- Niri window manager navigation, with some limited compatability with windows (e.g. uses Alt + F4 for close window and Alt + Tab for switching windows)
- Coding & Neovim navigation (e.g. commonly used symbols arranged to be intuitive, such as ^ to go to the left and $ to go to the right). Note that due to colemak layout I use arrows for navigation, which will break some configs but at least I can navigate while in insert mode. :^)
- Excel navigation (e.g. F2 & F4 easily accessible, ctrl & shift with arrows easy to access)
- PDF & Word document editting and viewing (e.g. macro above arrow keys will rapidly press arrow keys 4 times, which is sometimes easier for moving shapes)
- Video & Volume control with various media shortcuts on the media layer (e.g. volume controls, fast forward, skips, etc.) (Note: certain video controls may need config on your system in order to work)

It is easy to modify as it was made using Nick Coutsos' online visual editor. If you clone it and then link the repo to it you can easily modify it there. :^)

Typeractive Where I Bought My Keyboard:
https://typeractive.xyz/

Online Editor:
https://nickcoutsos.github.io/keymap-editor/

Happy Typing!

A few important notes:
- I use my keyboard over usbc, so I haven't properly set up any bluetooth.
- The ZMK build has been pinned to v0.2 as the github build failed otherwise. If you have a build fail issue, verify you are pinned to v0.2 not main.
https://zmk.dev/blog/2025/06/20/pinned-zmk
