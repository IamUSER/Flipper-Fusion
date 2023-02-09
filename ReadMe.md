<h1 align="center"><p>&#9762;<code>FZ Fusion Firmware</code>&#9762;</p></h1>

<p align="center">
  <img src="https://github.com/IamUSER/Flipper-Fusion/blob/main/images/hackboi.png?raw=true">
<br>
CODENAME: Purposeful Porpoise
</p>

<h2 align="center">Made Possible By:</h2>

<p align="center">
  <img src="https://user-images.githubusercontent.com/55334727/215170306-051eeb8f-8f72-437f-8c2d-0e4be009bdad.png">
</p>

This firmware is a complete overhaul of the [Official Firmware](https://github.com/flipperdevices/flipperzero-firmware), it also features lots of awesome code-bits from [Unleashed](https://github.com/DarkFlippers/unleashed-firmware).

-----
<br>
<h2 align="center">What makes FZ Fusion special?</h2>

<p>This is a fork of a fork of a fork. XFW Team spent many hours perfecting this code even further, and getting the most out of it. I just spent time screwing bolts into its neck...

This fork of Xtreme Firmware includes a HUGE RESOURCE LIBRARY with custom modifications and additions.

<i>Thanks to <b>FlipperZero, ClaraCrazy and XFW Contributors, Unleased Team, RogueMaster, UberGuidoZ, and many more!</b></i>

This firmware is xtra thicc because it attempts to include and organize many public asset repos that provide IR, SUB, NFC, IBTN, and other resources. I do not recommend this for well established Flippers! However if you are a new Flipper Operator and would like to take a quick shortcut, this will flash faster than you will find and aggragate all the included resource files.

If you just want the Resources check assets/resources and have fun!

<p align="center">
  <img src="https://github.com/IamUSER/Flipper-Fusion/blob/main/images/Passport.png?raw=true"><br>
P.S. I'm not here for drama, your money, or recognition. Hack4Peace! XO
<br><br>
<h2 align="center">Support the Upstream Project - XFM (Not Mine)</h2>

**If you like Xtreme Firmware and wish to help out, please contribute to the project ❤️**
<br>

- [Patreon](https://patreon.com/CynthiaLabs)
- `Monero`: 41kyWeeoVdK4quzQ4M9ikVGs6tCQCLfdx8jLExTNsAu2SF1QAyDqRdjfGM6EL8L9NpXwt89HJeAoGf1aoArk7nDr4AMMV4T
</p>

----
<br>
<h2 align="center">Roadmap:</h2>
Desimpification! Clara is great! The stock Xtreme assets... Not so much. Also simplify, expand, unify, and make the FlipperZero a PRO device.
<br><br>
Full roadmap: https://github.com/IamUSER/Flipper-Fusion/blob/main/documentation/roadmap.md

-----
<br>
<h2 align="center">Xtra [Xtreme] Settings:</h2>


XFW adds a powerful yet easy-to-use settings application, that gives you easy-access to the followign features:
<br>
<br>
<code>Base Graphics:</code> Change the fallback assets used. Its either OEM (default) or PRO
<br><code>Asset Pack:</code> Allows you to easily customize your firmware, more on that below 
<br><code>Anim Speed:</code> Speed in which the animations play
<br><code>Cycle Anims:</code> Duration of how long animations are played before switching to next
<br><code>Unlock Anims:</code> Custom setting just for PRO fallback animations.
<br><code>Battery style:</code> Classic Firmware battery style toggle, just at a more convenient place
<br><code>XP Level:</code> Changes your Flippers level
<br><code>SubGhz Extend:</code> Allows you to extend the subghz range beyond what FZ devs planned. (Potential Hardware Damage!)
<br><code>SubGhz Bypass:</code> Allows you to bypass the subghz region locks of the Flipper

<br clear="left"/>

-----
<br>
<h2 align="center">Animations / Asset Packs:</h2>

XFW adds a new & improved Animation / Asset system. It lets you to create and cycle through your own `Asset Packs` with only a few button presses, allowing you to easily load custom Animations and Icons like never before.

<img src="https://user-images.githubusercontent.com/55334727/214010675-9eddb8f5-1dd6-4cf4-a0ee-e37af8b6c933.PNG" align="left" width="200px"/>
You can easily create your own pack. Check <a href="https://github.com/ClaraCrazy/Flipper-Xtreme/wiki/1.-File-Formats">here</a> for a tutorial on creating your own. Essentially, add your own <code>Anims</code> & <code>Icons</code> folders, inside each <code>Asset Pack</code>.

<br clear="left"/>

<br>

<img src="https://user-images.githubusercontent.com/55334727/214016338-95a619c7-88d2-4db5-bb7a-75282d9082b8.png" align="left" width="200px"/>
Once you have some packs, upload them to your Flipper in <code>SD/dolphin_custom</code> (if you did this right you should see <code>SD/dolphin_custom/PackName/Anims</code> and/or <code>SD/dolphin_custom/PackName/Icons</code>).


<br clear="left"/>

<br>

<img src="https://user-images.githubusercontent.com/55334727/214013624-25dad48e-72ea-4a90-9060-66e137e0d61a.png" align="left" width="200px"/>
After installing the packs to Flipper, hit the <code>Arrow UP</code> button on the main menu and go to <code>Xtreme Settings</code>. Here choose which pack you want and tweak the other settings how you prefer, then press back to reboot and enjoy your new assets & animations!

<br clear="left"/>

-----
<br>
<h2 align="center">Levels:</h2>

This Firmware has 30 levels, not just the basic 3 the official one has.

With this new system in place, it allows for some cool stuff like locking animations behind a certain level. This can be done fairly easy: The idle_animations are tied to the level system. Specifically, the `Min level` variable of your manifest file is used here. Each level you reach, unlocks a new animation. The higher your level, the more animations people can see.

----
<br>
<h2 align="center">List of changes added to Official Firmware:</h2>

Note: This repo is always updated with select Xtreme Firmware main branch commits. Thank you to everyone who contribues!
<br><br>
Full(ish) changelog: https://github.com/IamUSER/Flipper-Fusion/blob/main/documentation/changelog.md

```txt
[Added in Fusion]

- Mifare files.
- Edit stock Xtreme Firmware to suit my maniacal ends.
- Make GUI more PRO.
- Add Asset Packs - Squatch, RM, Unleashed, etc.
- Restored the Status Bar!
- New Animations! (Feat. John Cena!)
- AirTag Emulator Firmware Mod added to resources. Not implemented! (https://github.com/culturally/flipper-zero-airtag)
- A plethora of useful assets for IR, SUB, NFC, IBTN, RFID, etc.
- A Thicc Sub Repo - https://github.com/SONNYRZ/Sub-GHz-Files-Flipper-Zero-
- Touchtunes Jukebox Remotes - https://github.com/jimilinuxguy/flipperzero-touchtunes
- OOK Bruteforcer - https://github.com/tobiabocchi/flipperzero-bruteforce
- Intercom RFID's - (https://github.com/wetox-team/flipperzero-goodies)
- t119 Bruteforcer - (https://github.com/xb8/t119bruteforcer)
- H10301 Bruteforce - (https://github.com/UberGuidoZ/Flipper)
```
```txt
[Added in XFW]

- Xtreme App
- Asset Packs
- More UI options
- A new battery display-type
- Scrolling view for long file names in browser
- NSFW Animations tied to the level system. Read more above
- Folder handling for empty ones (Now indicate they are empty)
- SFW Mode (OEM Mode in Fusion)
- Xtreme App
- Asset Packs
- More UI options
- A new battery display-type
- Scrolling view for long file names in browser
- PRO Animations tied to the level system. Read more above
- Folder handling for empty ones (Now indicate they are empty)
- Jamming Files
- Custom subghz presets
- Multiple NFC protocols
- Subghz and IR signal replication via gpio | Credits to @ankris812
- Honda Keys (CVE-2022-27254) & Ford blockers
- New API Routes for Locale settings
```
```txt
[Updated]

- Graphics Adjustments
- Folder handling for empty ones (Now indicate they are empty)
- Applications now use the new Locale setting
- Compiler now handles all non-compiled faps during build
- Compiler now accepts WIP SDK 
- Compiler just stfu about non-fatal problems
- Some further NFC stuff
- Weather App
- Applications now use above mentioned API Routes
- All Assets
- Tons of apps
- Massive compiler re-do
- About 1k files to speed things up a lot
- Applications to now use the new Locale setting
```
```txt
[Fixed]

- Bootloop and DFU Crashfix by jbohack
- Passport crash on high level
- OEM / Dummy_mode getting you XP
- Leveling system
- Mood system
```
```txt
[REMOVED]

- Unused Dummy Mode
- Broken apps (bad apple, chess, etc.)
- Tons of unused code from FAPs and system calls
```

-----
<br>

<h3> Manual Install</h3>

- Download the latest release (.zip) from [The releases tab](https://github.com/IamUSER/Flipper-Fusion/releases)
- Extract the archive. This is now your new Firmware folder
- Insert SD card into your PC and add the whole firmware folder to `SD/Update` and reinsert SD into the FlipperZero
- Power on the Flipper, hit the `Arrow Down` button, this will get you to the file menu. Hit `Arrow Left` once to enter the Browser, and then simply search for the 'updates' folder
- Inside that folder, select the Firmware folder you just added, and run the file thats simply called `Update`

----
<br>
<p align="center">
  <img src="https://github.com/IamUSER/Flipper-Fusion/blob/main/images/radioactive.gif?raw=true"><br></p>
<h2 align="center">Install this mutant firmware by building it yourself:</h2>
<h3 align="center">Freshest commits are in the <b>Reactor</b> branch!</h3>
<br><br>
<b>Requires USB Flash or Builtin Updater App!</b> Builtin updater is added to most custom firmware.
<br><br>

```bash
(Step 1)
To download the needed tools:
$ git clone --recursive https://github.com/IamUSER/Flipper-Fusion.git
$ cd Flipper-Fusion/

(Step 2)
Build apps:
$ ./fbt fap_dist

(Step 3)
Build resources:
$ ./fbt resources dolphin_ext

(Step 4)
Build firmware:
$ ./fbt COMPACT=1 DEBUG=0 updater_package

(Step 5 - Optional for rebuilds!)
Clean Build Cache (Repeat Step 4 afterward.)
$ ./fbt COMPACT=1 DEBUG=0 updater_package -c

(Step 6 - Preferred flash method!)
To flash directly to the Flipper (Needs to be connected via USB, qFlipper closed.)
After Firmware flash unpack resources.tar to SD. This is faster than Step 7.
$ ./fbt flash_usb

(Step 7 - Requires a custom firmware with builtin updater already be installed!)
Copy new firmware from the dist/f7-C/FZFusionx.xx.x?x folder to FlipperSD/updates.
Run the builtin updater in the same manner you update other custom firmware.
Wait for 2 hours! Unfortunately SD to SD updates take forever to unpack 220MB. 
```

**NOTE: If you are coming from a different/older firmware and encounter application errors, it is recommended to overwrite the "apps" folder on the SD card after updating by unpacking the "apps" folder from the resources.tar to the SD card. This folder houses all the .fap files, which may not update to the correct API versions by default. This does `NOT` remove any of your saved files! If you have custom apps installed you should know what you're doing.**
<br><br>
If you dont like the default asthetic, Xtreme Firmware added a SFW mode (OEM Mode in Fusion) to the Firmware. From the main menu, hit `Arrow UP` and select OEM Mode and now all assets will be stock.
<br><br>
**Reenable PRO mode with the steps listed below**
<br>

- Navigate to the main screen
- Press the UP button on the Flipper
- Press the 'PRO Mode' toggle
----
<br>
<h2 align="center">Awesome contributers and community additions ❤️</h2>

## GPIO
- [Lightmeter](https://github.com/oleksiikutuzov/flipperzero-lightmeter)
- [Air Mouse](https://github.com/ginkage/FlippAirMouse/)
- [Wifi Marauder](https://github.com/0xchocolate/flipperzero-firmware-with-wifi-marauder-companion)
- [Wifi Deauther](https://github.com/Timmotools/flipperzero_esp8266_deautherv2)
- [IFTTT Virtual Button for ESP8266 (By Ferrazzi)](https://github.com/Ferrazzi/FlipperZero_IFTTT_Virtual_Button)
- [Flashlight (By xMasterX)](https://github.com/xMasterX/flipper-flashlight)
- [GPIO Reader 1](https://github.com/biotinker/flipperzero-gpioreader)
- [GPIO Reader 2](https://github.com/aureli1c/flipperzero_GPIO_read)
- [Sentry Safe](https://github.com/H4ckd4ddy/flipperzero-sentry-safe-plugin)
- [Distance Sensor](https://github.com/Sanqui/flipperzero-firmware/tree/59656ca5fb644e0d4484259986b86a0b963f323d/applications/hc_sr04)
- [Temperature Sensor](https://github.com/Mywk/FlipperTemperatureSensor)
- [i2c Tools](https://github.com/NaejEL/flipperzero-i2ctools)
- [GPS](https://github.com/ezod/flipperzero-gps)
- [Mouse Jacker](https://github.com/mothball187/flipperzero-nrf24/tree/main/mousejacker)
- [Sniffer](https://github.com/mothball187/flipperzero-nrf24/tree/main/nrfsniff)
- [Scanner](https://github.com/vad7/nrf24scan)
- [ColecoVision Controller](https://github.com/ezod/flipperzero-rc2014-coleco)


## Games
- [Asteroids](https://github.com/antirez/flipper-asteroids)
- [2048](https://github.com/eugene-kirzhanov/flipper-zero-2048-game)
- [Arkanoid](https://github.com/DarkFlippers/unleashed-firmware/tree/dev/applications/plugins/arkanoid)
- [BlackJack](https://github.com/teeebor/flipper_games)
- [Doom](https://github.com/p4nic4ttack/doom-flipper-zero/)
- Multi Dice - In-house
- [Flappy Bird](https://github.com/DroomOne/flipperzero-firmware/tree/dev/applications/flappy_bird)
- [Game 15](https://github.com/x27/flipperzero-game15)
- [Game of Life (Updated to work by tgxn) (By itsyourbedtime)](https://github.com/tgxn/flipperzero-firmware/blob/dev/applications/game_of_life/game_of_life.c)
- Heap defense - Author Unknown
- [Mandelbrot Set (By Possibly-Matt)](https://github.com/Possibly-Matt/flipperzero-firmware-wPlugins)
- [Minesweeper](https://github.com/panki27/minesweeper)
- [Snake](https://github.com/flipperdevices/flipperzero-firmware/tree/dev/applications/plugins/snake_game)
- [Solitaire](https://github.com/teeebor/flipper_games)
- [Tetris](https://github.com/jeffplang/flipperzero-firmware/tree/tetris_game/applications/tetris_game)
- [Tic Tac Toe](https://github.com/gotnull/flipperzero-firmware-wPlugins/tree/420/applications/plugins/tictactoe_game)
- [Tamagotchi(By GMMan)](https://github.com/GMMan/flipperzero-tamagotch-p1)
- [Video Poker (By PixlEmly)](https://github.com/PixlEmly/flipperzero-firmware-testing/blob/420/applications/VideoPoker/poker.c)
- [Yatzee (By emfleak)](https://github.com/emfleak/flipperzero-yatzee)


## Misc
- [Authenticator (TOTP / HOTP)](https://github.com/akopachov/flipper-zero_authenticator)
- [Barcode Generator](https://github.com/McAzzaMan/flipperzero-firmware/tree/UPC-A_Barcode_Generator/applications/barcode_generator)
- [Caesar Cipher](https://github.com/panki27/caesar-cipher)
- Calculator - In house / notIntense
- [Counter](https://github.com/Krulknul/dolphin-counter)
- [Hex Viewer](https://github.com/QtRoS/flipper-zero-hex-viewer)
- [Mouse Jiggler](https://github.com/Jacob-Tate/flipperzero-firmware/blob/dev/applications/mouse_jiggler/mouse_jiggler.c)
- [Converter](https://github.com/theisolinearchip/flipperzero_stuff/tree/main/applications/multi_converter)
- [Vibrator](https://github.com/qqmajikpp/flipperzero-firmware-wPlugins/tree/420/applications/plugins/orgasmotron)
- [Paint](https://github.com/n-o-T-I-n-s-a-n-e)
- [UART Echo](https://github.com/flipperdevices/flipperzero-firmware/pull/831)
- [USB HID Autofire](https://github.com/pbek/usb_hid_autofire)
- [USB Keyboard & Mouse](https://github.com/huuck/FlipperZeroUSBKeyboard) / (https://github.com/DarkFlippers/unleashed-firmware)
- [Wii EC Analyzer](https://github.com/csBlueChip/FlipperZero_WiiEC)


## Music
- [BPM Tapper (By panki27)](https://github.com/panki27/bpm-tapper)
- [Metronome](https://github.com/panki27/Metronome)
- [Morse Code](https://github.com/DarkFlippers/unleashed-firmware/pull/144)
- Music Beeper - Author Unknown
- [Music Player](https://github.com/flipperdevices/flipperzero-firmware/pull/1189)
- [Ocarina](https://github.com/invalidna-me/flipperzero-ocarina)
- [Software Automatic Mouth aka SAM](https://github.com/ctoth/SAM)
- [Tuning Fork](https://github.com/besya/flipperzero-tuning-fork)
- [Music Tracker](https://github.com/DrZlo13/flipper-zero-music-tracker)


## Tools
- [Bluetooth Remote](https://github.com/flipperdevices/flipperzero-firmware/pull/1330)
- [Clock](https://github.com/kowalski7cc/flipperzero-firmware/tree/clock-v1) / In house
- [Countdown Timer](https://github.com/0w0mewo/fpz_cntdown_timer)
- [DAP Link](https://github.com/flipperdevices/flipperzero-firmware/pull/1897)
- [DTMF](https://github.com/litui/dtmf_dolphin)
- [Dolphin Backup & Restore](https://github.com/flipperdevices/flipperzero-firmware/pull/1384)
- [iButton Fuzzer](https://github.com/DarkFlippers/unleashed-firmware)
- [NFC Magic](https://github.com/flipperdevices/flipperzero-firmware/pull/1966)
- [POCSAG Pager](https://github.com/xMasterX/flipper-pager)
- [Password Generator](https://github.com/anakod/flipper_passgen)
- [PicoPass](https://github.com/flipperdevices/flipperzero-firmware/pull/1366)
- [RFID Fuzzer](https://github.com/RogueMaster/flipperzero-firmware-wPlugins/pull/245)
- [Spectrum Analyzer](https://github.com/jolcese/flipperzero-firmware/tree/spectrum/applications/spectrum_analyzer)
- [Sub-Ghz Bruteforce](https://github.com/derskythe/flipperzero-subbrute/tree/master)
- [Sub-Ghz Playlist](https://github.com/darmiel/flipper-playlist)
- [Protocol Visualizer](https://github.com/antirez/protoview)

----
<br>
<h2 align="center">Known Bugs:</h2>

<p>
- After upgrading to multiple different firmware your Flipper may run out of builtin memory. If you cannot update this is likely the case. You will need to clear your internal storage from the Settings > Storage Menu. You may lose settings and XP! Use the Xtra Settings to readjust your XP as needed.
<p>

----
<br>
<h2 align="center">Credits:</h2>

<p>
- <a href="https://github.com/flipperdevices/flipperzero-firmware">FlipperZero Team</a> - Stock Firmware and the epic FlipperZero!<br>
- <a href="https://github.com/ClaraCrazy/Flipper-Xtreme">ClaraCrazy</a> - Xtreme Firmware<br>
- <a href="https://github.com/DarkFlippers/unleashed-firmware">DarkFlippers</a> - Unleashed Firmware and Apps<br>
- <a href="https://github.com/RogueMaster/flipperzero-firmware-wPlugins">RogueMaster</a> - w/Plugins<br>
- <a href="https://github.com/UberGuidoZ/Flipper">UberGuidoZ</a> - Centralizer of quality flipper files!<br>
</p>

----
<h2 align="center">Contributors</h2>
<p align="center">
  <img src="https://user-images.githubusercontent.com/55334727/212134625-21383102-02f3-453f-b1d7-8a9c65b27612.svg">
</p>

----
<p align="center"> "What we do for ourselves dies with us. What we do for others and the world remains and is immortal.” ― Albert Pine </p>
