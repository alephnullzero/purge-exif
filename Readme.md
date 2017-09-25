# Purge-Exif

This utility is designed for Termux. It will purge all exif metadata from all pictures and videos.

## Installation
1. Install termux
1. Enable termux access to your device's storage
	```bash
	termux-setup-storage
	```
1. Install perl: `pkg install perl`
1. Download exiftool by Phil Harvey from his site. Follow the Readme to install exiftool
1. Create a soft link of `purge-exif.bash` to `~/.shortcut`. You can run `purge-exif` right from a widget.

