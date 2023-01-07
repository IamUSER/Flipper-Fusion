<h1 align="center"><p>&#9762; Flipper <code>Fusion</code> Firmware &#9762;</p></h1>

<p align="center">
  <img src="https://github.com/IamUSER/Flipper-Fusion/blob/main/hackboi.png?raw=true">
<br>
CODENAME: Purposeful Porpoise
</p>

-----
<br>
<h2 align="center">What makes it special?</h2>

<p>If you can't tell... This is a fork of a fork of a fork. 
<br><br>
<i>Thanks to <b>FlipperZero, Unleased Team, RogueMaster, ClaraCrazy, and UberGuidoZ.</b></i>
<br><br>
This firmware is very large because it attempts to include and organize many public asset repos that provide IR, SUB, NFC, IBTN, and other resources.
<br><br>
<b>No excuses: I am new to GitHub and coding in general, please let me know if I have not properly attributed your work. Submit a pull request and I will validate and promote your work.</b>
<br><br>
<p align="center">
  <img src="https://github.com/IamUSER/Flipper-Fusion/blob/main/Passport.png?raw=true"><br>
P.S. I'm not here for childish arguments, your money, or recognition. Hack4Peace! XO
<br><br>
<h2 align="center">Support the Upstream Project - XFM (Not Mine)</h2>

**If you like Xtreme Firmware and wish to help out, please contribute to the project ❤️**
<br>

- [Bunq - My bank](https://bunq.me/ClaraK)
- [Paypal](https://paypal.me/RdX2020)
- [Patreon](https://patreon.com/CynthiaLabs)
- `Monero`: 41kyWeeoVdK4quzQ4M9ikVGs6tCQCLfdx8jLExTNsAu2SF1QAyDqRdjfGM6EL8L9NpXwt89HJeAoGf1aoArk7nDr4AMMV4T
</p>

----
<br>
<h2 align="center">Roadmap:</h2>

<p>I just want to simplify, expand, unify, and make the FlipperZero a professional use device. Ya know, where your friends and colleagues don't think you're a porn obsessed weeb. Hack for peace! XO
<br><br>
Full roadmap can be found at https://github.com/IamUSER/Flipper-Fusion/blob/main/documentation/RoadMap.md

----
<br>
<h2 align="center">Install my mutant firmware by building it yourself:</h2>

```bash
To download the needed tools:
$ git clone --recursive https://github.com/IamUSER/Flipper-Fusion.git
$ cd Flipper-Fusion/

To flash directly to the Flipper (Needs to be connected via USB, qFlipper closed)
$ ./fbt flash_usb

To just compile firmware
$ ./fbt updater_package

If building FAPS:
$ ./fbt fap_dist

If building image assets:
$ ./fbt resources icons dolphin_ext
or
$ ./fbt resources dolphin_ext
```

**NOTE: If you are coming from a different FW, it is recommended to delete / clear your "apps" folder on the SD card prior to updating. This folder houses all the .fap files, which do not update to the correct API versions by default if old ones are present (Thanks flipper devs). This does `NOT` remove any of your saved files!**
<br><br>
If you dont like the default asthetic, ClaraCrazy added an SFW mode (Now PRO Mode) to the Firmware. From the main menu, hit `Arrow UP` and select PRO Mode and now all assets will be stock.
<br><br>
**Enable PRO mode with the steps listed below**
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


---

-----
<br>
<h2 align="center">List of changes:</h2>

Note: This repo is always updated with Xtreme and upstream repos. No need to mention all those here. We will only mention **our** changes that we can actually be credited for, unlike *others*

```txt
[Added in Fusion]

- Restored the Status Bar!
- A plethora of useful assets for IR, SUB, NFC, IBTN, RFID, etc.
- A Thicc Sub Repo - https://github.com/SONNYRZ/Sub-GHz-Files-Flipper-Zero-
- Touchtunes Jukebox Remotes - https://github.com/jimilinuxguy/flipperzero-touchtunes
- OOK Bruteforcer - https://github.com/tobiabocchi/flipperzero-bruteforce
- Intercom RFID's - (https://github.com/wetox-team/flipperzero-goodies)
- t119 Bruteforcer - (https://github.com/xb8/t119bruteforcer)
- H10301 Bruteforce - (https://github.com/UberGuidoZ/Flipper)
```
```txt
[Added]

- SFW Mode (PRO Mode in Fusion)
- Jamming Files
- Custom subghz presets
- Subghz and IR signal replication via gpio | Credits to @ankris812, exact commit lost to time as of rn
- Honda Keys (CVE-2022-27254)
- NSFW Animations tied to the level system. Read more above
- New API Routes for Locale settings
- Scrolling view for long file names in browser
- Tamagotchi rom
```
```txt
[Updated]

- All graphics
- Folder handling for empty ones (Now indicate they are empty)
- Applications now use the new Locale setting
- Compiler now handles all non-compiled faps during build
- Compiler now accepts WIP SDK 
- Compiler just stfu about non-fatal problems
- Some further NFC stuff
- Weather App
- Applications now use above mentioned API Routes
```
```txt
[Fixed]

- Passport crash on high level
- SFW / Dummy_mode getting you XP
- Leveling system
- Mood system
```
```txt
[REMOVED]

- Unused Dummy Mode
- Broken apps (bad apple, chess, etc.)
- Unused code from FAPs and system calls
```

----
<br>
<h2 align="center">Known Bugs:</h2>

```txt
- Name Changer app crashes when you close it without using it
```

----
<br>
<h2 align="center">Credits:</h2>

<p>
- <a href="https://github.com/flipperdevices/flipperzero-firmware">FlipperZero Team</a> - Stock Firmware and the epic FlipperZero!<br>
- <a href="https://github.com/ClaraCrazy/Flipper-Xtreme">ClaraCrazy</a> - Xtreme Firmware<br>
- <a href="https://github.com/DarkFlippers/unleashed-firmware">DarkFlippers</a> - Unleashed Firmware and Apps<br>
- <a href="urlhttps://github.com/RogueMaster/flipperzero-firmware-wPlugins">RogueMaster</a> - w/Plugins<br>
- <a href="https://github.com/UberGuidoZ/Flipper">UberGuidoZ</a> - Centralizer of quality flipper files!<br>



