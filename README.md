# BK Arcade

[Play BK Arcade](https://oizmerly.github.io/bk-arcade/)

A self-contained BK-0010(01) arcade with Bolder Dash, Bolder Dash 2M, Jetman,
Planet of Zoom, Captain Comic, Breaking Ball, Digger, Runing, Flasse, and
Soldier missions 1, 2, and 3, King's Valley, Exolon, and Desantnik.

Download `index.html` to play offline. All programs, cassette data, images,
firmware, audio code, and the 74-key BK keyboard are embedded in that one file.
There are no external JavaScript libraries, packages, fonts, or network requests.
USB/Bluetooth controllers use the original joystick inputs, or keyboard inputs
for King's Valley. The joystick icon opens device selection and calibration.

Phone controls support sliding directions and simultaneous movement and fire.
Audio starts after a completed tap and can resume after switching apps.

The 2M selector entry uses the supplied BOLDER2.BIN (also named BOLDE2.BIN).
Its own title says Bolder Dash; the 2M suffix is not independently confirmed.
Soldier 2 and 3 use the shared engine and original mission data files.
Exolon.bin and Exolon.ovl belong to the same game. Both are embedded; the
original cassette routine loads EXOLON.OVL automatically. Arrows move, jump,
and duck; Space fires and X launches a rocket.

Desantnik has five compact part tabs above the screen: Flight, Race, Search,
Labyrinth, and Headquarters. Each opens its part directly. Links #desan-1 through
#desan-5 select a part; Restart keeps that selection. The original menu remains
available from Help. All five overlays stay embedded and load automatically.
Phone actions follow the current part; controller buttons 1–5 provide the final
part's five strikes.

Original programs credit MRLC, SWcorp, SHW&AW, BIL corp., DIM corporation,
Shishkin Software, and Soft of Future. Exolon also includes a KingSoft/SMC
introduction.
The Soldier loader also carries a KingSoft credit. The BK monitor firmware is
from the [BkEmu firmware collection](https://github.com/3cky/bkemu-android/blob/master/app/src/main/res/raw/monit10.rom).
The games and firmware remain the work of their original authors.
The JavaScript runtime and frontend were written for this project.
