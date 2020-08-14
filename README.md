# Thinkpad T430s Hackintosh
- Based on (this guide)[https://github.com/drasbeck/macos-thinkpad-t430].
- SSDT and DSDT has been patched.
- Remember to regenerate your own ``SMBIOS`` information.
- All basic features are functioning stably. Have been this machine as my daily driver for coding in the past 6 months and haven't encountered any serious disorder so far.

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
- Caddybay.
- Ethernet.
- Wifi (using a ``Comfast CF-811AC dongle``).

## Partially working
- ThinkPad ~~nipple~~ TrackPoint.

## Not tested
- DisplayPort audio.
- Internal mic (my internal is also broken).
- Webcam (my webcam is also broken).

## Not working
- Bluetooth (with default BCM card).
- Maybe something else I haven't tested?

<img src="https://raw.githubusercontent.com/phathung2001/phathung2001/master/terminal.png"/>
