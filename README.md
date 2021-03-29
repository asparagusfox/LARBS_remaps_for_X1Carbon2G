# useful_remaps_for_X1Carbon2G

Shell script for vim friendly (swap caps and esc) remapping on the Lenovo Thinkpad X1 Carbon 2nd Gen. For some reason this laptop has a weird placement of the home and end keys, where caps lock should usually be! The new "esc" key will act as super when pressed once.

## What it Does
- Increase key speed via a rate change
- Makes Shift-Esc ~
- Swaps left super and end key
- When end is pressed once it is treated as escape
- When super is held it acts as super, when pressed once it acts as end

## Dependencies
- xorg-xset
- xorg-xmodmap
- xcape

## Usage

For easy usage add to `$PATH`.

Easy way to run this script on X session start: Append filename to `$HOME/.xprofile`.

If using Lukesmithxyz's LARBS, replace the remaps script within `$HOME/.local/bin`, this will run the script after using the`startx` command.
