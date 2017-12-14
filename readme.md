# Enhanced Touchscreen Gestures #

* Author: Joseph Lee
* Download [stable version][1]

This add-on provides additional touchscreen gestures for NVDA. It also provides a set of gestures for easier browse mode navigation.

Note: this add-on requires NVDA 2017.4 or later running on a touchscreen computer with Windows 8.1 or 10.

## Commands

### Available everywhere

* 4 finger double tap: toggle input help mode.
* Tap and hold: performs right click at the object under your finger.
* Four finger flick right: toggle touch keyboard (usually enables it).

### Object mode

* 3 finger flick down: read current window.
* 3 finger flick left: report object with focus.
* 3 finger flick right: report current navigator object.
* 4 finger flick up: report title of the current window.
* 4 finger flick down: report status bar text.

## Web touch mode

This touch mode, available in browse mode, allows you to navigate the document by selected element. To switch to web mode, from browse mode documents, perform 3 finger tap. From this mode, flicking up or down with one finger cycles through available element navigation modes, while flicking right or left with one finger moves to next or previous chosen element, respectively. Once you move away from browse mode documents, object touch mode is used.

## Synth settings touch mode

You can use this mode to quickly change synthesizer settings such as choosing a voice and changing volume. In this mode, use two finger flick left or right to move between synth settings and use two finger flick up and down gestures to change values. This gestures mirrors that of synth settings ring commands on the keyboard.

## Coordinate announcement beep

If you've enabled play mouse coordinates setting in mouse settings, you'll hear beeps to indicate current screen coordinate when you invoke touch exploration gestures.

## Screen orientation

If you are running NvDA 2017.3 or earlier, NVDA can announce screen orientation changes. Note that NvDA cannot distinguish between primary and secondary orientation at this time, and this feature is now part of NVDA as of 2017.4.

## Touch keyboard

With the add-on installed, when typing on the touch keyboard, you need to perform a double tap in order to press keys (termed standard typing). You can change it to touch typing (where you let go of the key and the key will be pressed) by going to NVDA menu/Preferences/Touch Interaction and checking touch typing checkbox.

## Touch command passthrough

An unassigned command is available to allow you to use touchscreen gestures as though NVDA is not running. In order to use this, you need to assign a command (via Input Gestures dialog) under Enhanced Touch Gestures category to let you do this for up to ten seconds or toggle this manually. Then go to NVDA menu/Preferences/Touch Interaction, then configure pause NVDA's touch command value between 3 to 10 seconds (default is 5 seconds).

## Version 17.10

* Due to support policy from Microsoft, Windows 8 (original release) is no longer supported.
* NVDA will no longer announce screen orientation twice when running NVDA 2017.4 development snapshots.

## Version 17.07.1

* Added an option in touch interaction dialog to manually toggle touch passthrough without use of a timer.
* With manual passthrough mode off, if touch passthrough is turned on before the passthrough duration expires, touch interaction would be enabled.

## Version 17.07

* Added a new dialog named Touch Interaction under NVDA's preferences menu to configure how NVDA works with touchscreens.
* After installing this version, when pressing keys on the touch keyboard, one must double tap the desired key. You can switch back to the old way by enabling touch typing from Touch Interaction dialog.
* Added a command (unassigned) to allow NVDA to ignore touch gestures for up to 10 seconds.
* Added an option in Touch Interaction dialog to allow NVDA to pause touch interaction between 3 to 10 seconds in order to perform touchscreen gestures directly (as though NVDA is not running; default is 5 seconds).
* Added debug logging messages when performing right clicks (tap and hold) to be recorded in the NVDA log (requires NVDA 2017.1 or later).
* Due to changes made when playing screen coordinates, NVDA 2017.1 or later is required.

##Version 17.03

* Fixed an issue where coordinate announcement beep did not play or an error tone played instead when using NVDA 2017.1 or later.

##Version 16.12

* Web touch mode works in Microsoft Edge, Microsoft Word and others where browse mode is used.
* Added lists and landmarks to web touch mode elements.

## Version 16.06

* Initial stable version.

[1]: http://addons.nvda-project.org/files/get.php?file=ets
