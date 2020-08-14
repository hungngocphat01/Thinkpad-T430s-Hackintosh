# Thinkpad T430s Hackintosh
- Based on [this guide](https://github.com/drasbeck/macos-thinkpad-t430).
- SSDT and DSDT has been patched.
- Remember to regenerate your own ``SMBIOS`` information.
- All basic features are functioning stably. Have been using this machine as my daily driver for coding, photo editing, office stuffs in the past 6 months and haven't encountered any serious disorder so far.
<div align="center">
<img src="https://raw.githubusercontent.com/phathung2001/Thinkpad-T430s-Hackintosh/master/Screen%20Shot%202020-08-14%20at%206.30.32%20PM.png"/>
<div/>

## My specs
- Model: Thinkpad T430s.
- CPU: Intel Core i5-3320M.
- iGPU: Intel HD Graphics 4000.
- RAM: 8 GB.
- Display: TN 1600x900.
- SSD: Crucial BX500 (250GB).
- HDD (caddybay): WD something 500 GB. I forgot its model.

## Working (as I tested so far).
- Boot.
- Brightness control.
- Sleep (``sleepmode 0``).
- Audio (``VoodooHDA``).
- Audio jack (external mic is also working).
- Battery percentage.
- Keyboard (``Fn`` keys are working as well).
- Trackpad.
- Caddybay.
- Ethernet.
- Wifi (using a ``Comfast CF-811AC dongle``).
- USB ports.

## Partially working
- ThinkPad ~~nipple~~ TrackPoint (moving like a stair).

## Not tested
- DisplayPort audio.
- Internal mic (my hardware internal mic is broken).
- Webcam (my hardware webcam is also broken).

## Not working
- Bluetooth (with default BCM card).
- Maybe something else I haven't tested?

<div align="center">Hackurman<div/>
<img src="https://raw.githubusercontent.com/phathung2001/phathung2001/master/terminal.png"/>
