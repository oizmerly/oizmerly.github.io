# BK Arcade

[Play BK Arcade](https://oizmerly.github.io/bk-arcade/)

A self-contained BK-0010(01) arcade with 25 alphabetically sorted selections:
Bolder Dash, Bolder Dash 2M, Boulder Dash, Breaking Ball, Captain Comic, Cosmic Builder,
Desantnik, Digger, Exolon, Expert, Flasse, Flier, Jetman, King's Valley,
Lode Runner, Pereval, Planet of Zoom, Runing, Saper, Savage_D (demo),
Soldier 1–3, Tetris, and Xonix.

Download `index.html` to play offline. Programs, cassette data, previews,
firmware, audio code, and the 74-key BK keyboard are embedded in that file.
There are no external libraries, packages, fonts, or network requests.

The desktop library scrolls within a full-height sidebar, alongside a larger
display that reserves room for the BK keyboard when it fits. Short windows
keep an expandable Keyboard row; manual open/close choices survive resizes.
The keyboard has 74 drawn keycaps with corrected proportions, Cyrillic/Latin
legends, and outline symbols. It scales uniformly to preserve the key shapes.
Phones keep the horizontal game strip, sliding direction controls,
simultaneous movement and actions, and gesture-activated audio.
USB/Bluetooth controllers use each game's original joystick or keyboard input.
The joystick icon opens device selection and calibration.

Jetman, Breaking Ball, Captain Comic, Flier, and Planet of Zoom return safely
from their original control selectors to the title menu, preserving keyboard,
joystick, combined-mode, and key-binding settings.

Pereval, Lode Runner, and Expert include their `.GMS` files. Exolon includes
`EXOLON.OVL`; Captain Comic and Soldier include their companion level files.
The games' original cassette routines load these embedded files automatically.
Savage_D is the supplied self-running demonstration, labelled Demo in the library.

Desantnik has five direct part tabs: Flight, Race, Search, Labyrinth, and
Headquarters. Links #desan-1 through #desan-5 select a part; Restart keeps that
selection. The original menu remains available from Help. All five overlays
are embedded. Phone and controller actions follow the current part, including
the final part's five strikes.

The separate Boulder Dash port comes from [blairecas/bolder_bk0010](https://github.com/blairecas/bolder_bk0010/tree/main/release), pinned to commit `cc790ade5af9affc70ede4b37007e524bd03c733`. Its original binary, 20 caves, and native joystick controls are embedded. Graphics are credited to Neo Spectrum Man. Arrows move, Z grabs, and Space centres the view.

The 2M entry uses the supplied BOLDER2.BIN (also named BOLDE2.BIN). Its own title
says Bolder Dash; the 2M suffix is not independently confirmed.

The programs and firmware remain the work of their original authors.
The monitor comes from the [BkEmu firmware collection](https://github.com/3cky/bkemu-android/blob/master/app/src/main/res/raw/monit10.rom).
The dependency-free JavaScript runtime and frontend were written for this project.
