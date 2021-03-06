dwm - dynamic window manager
============================

This is a clone of [suckless.org](https://dwm.suckless.org/) dynamic window manager for X **dwm** with my customizations.

## Customizations

 - [notitle](https://dwm.suckless.org/patches/notitle/)
 - [scratchpad](https://dwm.suckless.org/patches/scratchpad/)
 - [fullscreen](https://dwm.suckless.org/patches/fullscreen/)
 - [ru_gaps + ru_centeredmaster](https://dwm.suckless.org/patches/ru_gaps/)

## How it was done

	cd src
	patch < ../patches/dwm-notitle-6.2.diff
	patch < ../patches/dwm-scratchpad-6.2.diff
	patch < ../patches/dwm-fullscreen-6.2.diff
	patch < ../patches/dwm-ru_gaps-6.2.diff
	patch < ../patches/dwm-ru_centeredmaster-6.2.diff

## Installation

Read `README` in `src` folder
