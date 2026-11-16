# BK Arcade

[Play BK Arcade](https://oizmerly.github.io/bk/)

A self-contained BK-0010(01) arcade with Bolder Dash, Bolder Dash 2M, Jetman,
Planet of Zoom, Captain Comic, Breaking Ball, Digger, Runing, Flasse, and
Soldier missions 1, 2, and 3.

Download `index.html` to play offline. All programs, cassette data, images,
firmware, audio code, and the 74-key BK keyboard are embedded in that one file.
There are no external JavaScript libraries, packages, fonts, or network requests.
USB/Bluetooth controllers use each game's original joystick inputs; the joystick
icon opens device selection and calibration.

The 2M selector entry uses the supplied BOLDER2.BIN (also named BOLDE2.BIN).
Its own title says Bolder Dash; the 2M suffix is not independently confirmed.
Soldier 2 and 3 use the shared engine and original mission data files.

Original programs credit MRLC, SWcorp, SHW&AW, BIL corp., and DIM corporation.
The Soldier loader also carries a KingSoft credit. The BK monitor firmware is
from the [BkEmu firmware collection](https://github.com/3cky/bkemu-android/blob/master/app/src/main/res/raw/monit10.rom).
The games and firmware remain the work of their original authors.
The JavaScript runtime and frontend were written for this project.
