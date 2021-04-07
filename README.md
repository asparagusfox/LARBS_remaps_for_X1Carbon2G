# useful_remaps_for_X1Carbon2G

Script to remap some keys to make the ThinkPad X1 Carbon (Second Generation) easier to use, especially for Vim.

This laptop has a weird keyboard layout!

## What it Does
- Increase autorepeat speed
- Makes Shift-Esc ~
- Swaps left super and end key (Easier access)
- When end is pressed once it is treated as escape (For Vim)
- When (physical key) super is held it acts as super, when pressed once it acts as end

Hopefully this makes sense!

## Dependencies
- xorg-xset
- xorg-xmodmap
- xcape

## Usage

Run this script upon starting X by adding it to `.xinitrc` or `.xprofile`.
