# useful_remaps_for_X1Carbon2G

Remap keys to make the ThinkPad X1 Carbon (Second Generation) easier to use, especially for Vim.
This laptop has a weird keyboard layout!

## What it Does
- Increase autorepeat speed
- Makes Shift-Esc ~
- End becomes Super (Easier access)
- When End is pressed once it is treated as Escape (For Vim)
- (Physical) Super becomes End

Hopefully this makes sense!

## Dependencies
- xorg-xset
- xorg-xmodmap
- xcape

## Usage

Run this script upon starting X by adding it to `.xinitrc` or `.xprofile`.
