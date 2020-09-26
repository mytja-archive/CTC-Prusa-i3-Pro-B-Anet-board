# CTC Prusa i3 Pro B with Anet Board
CTC Prusa i3 Pro B upgrades with Anet board

Manual for 3d printer assembly: https://cdn.thingiverse.com/assets/f6/95/9e/ad/74/Manual.pdf

# Steps for upgrading your 3d printer

Download this repository and unpack it

## 1. Upgrade Marlin

### Marlin is still in developement! Upgrade at your own risk!

1. Download newest Arduino IDE from here: https://www.arduino.cc/en/Main/Software
2. Go to folder of Arduino IDE and search for folder hardware
3. Go into it and unzip Anet.zip file, you can find in this repository
4. Start Arduino IDE and open Marlin.ino file
5. Follow this tutorial without step 5: https://www.instructables.com/id/HOW-TO-FIX-ANET-BRICKED-BOARD-USING-AN-ARDUINO-UNO/
6. Then remove ISP Arduino and connect a 12v power supply to your Anet board.
7. Plug USB cable into your computer and in Arduino IDE select following settings - Board: Anet 1.0 (Optiboot) and Programmer: AVRISP mkII
8. Select also a serial port and click verify
9. If it compiles without errors, then click upload.

Note, that you might have to change some settings in Configuration.h file, but internet is always helpful. You can check https://marlinfw.org for more informations.

## 2. 3d print new stuff

- https://www.thingiverse.com/thing:2203796 or https://www.thingiverse.com/thing:2368907 - new extruder (That didn't work for me)
- https://cad.onshape.com/documents/19546743ae62b6bb83ce822a/w/bcdc97cd20c3a52905c4439f/e/5016297ffb41d91eea07c345 - Z axis holder with holder for tools (My own work and can be also cut with a laser)
- https://www.thingiverse.com/thing:2771497 - new Z axis joiner
- https://www.thingiverse.com/thing:2353994 - new fan
- https://www.thingiverse.com/thing:2646220 - anti wobble
- https://www.thingiverse.com/thing:2820627 or https://cad.onshape.com/documents/7c3645d1193ffe3f57eaf46a/w/72a3172bb260654d2ab974bd/e/68626099921b1b2b9746ab77 - Power supply protector
- https://www.thingiverse.com/thing:2869098 - LCD backcover (always nice to have)
- https://www.thingiverse.com/thing:2907985 - Anti vibration for Z axis stepper motor

## 3. And now, install all new stuff on a 3d printer

## Bonus - if anything original breaks:

- https://www.thingiverse.com/thing:2619519 - Y axis motor holder
- https://www.thingiverse.com/thing:2293742 - Y belt holder (not sure if it's compatible with CTC Prusa)

## Bonus - also great to have

- https://www.thingiverse.com/thing:2629088 - SD card holder
- https://www.thingiverse.com/thing:2038979 and https://www.thingiverse.com/thing:2039990 - "cadena eye" (wiring management)
- https://www.thingiverse.com/thing:2644452 - LED cluster
- https://www.thingiverse.com/thing:2343415 - Z foot
- https://www.thingiverse.com/thing:2117597 - Anti vibration plywood feet
- https://www.thingiverse.com/thing:2784329 - Z knob for bed levelling

## You can always search here: https://www.thingiverse.com/search?q=ctc+prusa+i3+pro+b for even more stuff

## Calibration

Here is a calibration G-code, that I wrote by myself: https://github.com/mytja/Calibration/tree/master/Prusa%20i3%20Pro%20B%20-%20clone

You did it. Congratulations. Your 3d printer is now a lot better than before.
