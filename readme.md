### O&OSU10.reg
`O&OSU10 (O&O ShutUp10++)` is a program used for debloating windows. `O&OSU10.reg` was made from the application [O&O ShutUp10++](https://www.oo-software.com/en/shutup10) on a Windows 10 Pro 2H22 system, using [Procmon](https://learn.microsoft.com/en-us/sysinternals/downloads/procmon) to get registery keys from `O&OSU10` and make `O&OSU10.reg`. 

This reg file contains all settings from `O&OSU10`, and is very easily customizable using any text editor.

`O&OSU10` actually had more than 10 settings that either didn't work or did something completely different from what it said it does, and I had to do some research to find replacement reg keys.
#

Important Notes:
- Extra reg keys were added under windows update `(hide windows update notifications completely, and do not automaticly download updates (only works on windows pro))`
- The current settings are setup for consumers `(not for people who want to disable everything)`, and should not break anything `(windows store, update and defender should all work)`
- There are definately better open source projects for tweaking windows, check out:
  1. [[privacy.sexy](https://privacy.sexy)][[github](https://github.com/undergroundwires/privacy.sexy)] `(makes a .bat file that you can run on any system)`
#

For people who do not have a good text editor: Use [Notepad++](https://notepad-plus-plus.org/)
>If you are using Notepad++ for the first time, here are some settings/hotkeys that can help:
>- Settings
>   - Settings (at the top) -> Preferences -> Dark Mode
>- Hotkeys
>   - Ctrl+K and Ctrl+Shift+K: used to comment/uncomment lines (with text selected)
>   - Ctrl+Z and Ctrl+Shift+Z: used to undo/redo edits
