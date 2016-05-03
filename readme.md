# Enhanced Touchscreen Gestures #

* Author: Joseph Lee
* Version: [0.5][1]

This add-on provides additional touchscreen gestures for NVDA. It also provides a set of gestures for easier browse mode navigation.

Note that you need NVDA 2012.3 or later installed on a touchscreen computer running Windows 8 or later.

## Commands ##

### Available everywhere ###

* 4 finger double tap: toggle input help mode.
* Tap and hold: performs right click at the object under your finger.
* Four finger flick right: toggle touch keyboard (usually enables it).

### Object mode ###

* 3 finger flick down: read current window.
* 3 finger flick left: report object with focus.
* 3 finger flick right: report current navigator object.
* 4 finger flick up: report title of the current window.
* 4 finger flick down: report status bar text.

## Web touch mode ##

This touch mode, available in browse mode, allows you to navigate the document by selected element. To switch to web mode, from browse mode documents, perform 3 finger tap. From this mode, flicking up or down with one finger cycles through available element navigation modes, while flicking right or left with one finger moves to next or previous chosen element, respectively. Once you move away from browse mode documents, object touch mode is used.

## Synth settings touch mode

You can use this mode to quickly change synthesizer settings such as choosing a voice and changing volume. In this mode, use two finger flick left or right to move between synth settings and use two finger flick up and down gestures to change values. This gestures mirrors that of synth settings ring commands on the keyboard.

## Coordinate announcement beep ##

If you've enabled play mouse coordinates setting in mouse settings, you'll hear beeps to indicate current screen coordinate when you invoke touch exploration gestures.

## Screen orientation ##

NVDA can announce screen orientation changes. Note that NvDA cannot distinguish between primary and secondary orientation at this time.

[1]: http://addons.nvda-project.org/files/get.php?file=ets
