# Dudisks

Mount and unmount removables with dmenu-like utilities and udisks on demand.

## Requirements

 * lsblk
 * udisks2
 * dmenu
 * notify-send (optional)
 * xclip (optional)

## Installation

 * Put 10-udisks2.rules in `/etc/polkit-1/rules.d/` or `/usr/share/polkit-1/rules.d` . This will allow you to mount removables without asking for a root password. Adjust group `plugdev` to whatever is used in your distro
 * Put the script in your `$PATH`
 * Bind it to a key in your wm

## Notes

The script is a very basic hack. I've been asked to show how I deal
with removables with on-demand mount, thus this repo exist, but I
strongly advise you to consider reading the scrip before using it.
