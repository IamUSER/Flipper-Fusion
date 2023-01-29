<h1 align="center"><p>&#9762; Flipper <code>Fusion</code> Firmware &#9762;</p></h1>

<p align="center">
  <img src="https://github.com/IamUSER/Flipper-Fusion/blob/main/images/hackboi.png?raw=true">
<br>
CODENAME: Potent Puffer
</p>

  <img src="https://user-images.githubusercontent.com/55334727/215170306-051eeb8f-8f72-437f-8c2d-0e4be009bdad.png">
</p>

[Intro](https://github.com/ClaraCrazy/Flipper-Xtreme#What-makes-it-special) | [Animations](https://github.com/ClaraCrazy/Flipper-Xtreme#Animations--Asset-Packs) | [Docs](https://github.com/ClaraCrazy/Flipper-Xtreme/wiki) | [Changelog](https://github.com/ClaraCrazy/Flipper-Xtreme#list-of-changes) | [Known bugs](https://github.com/ClaraCrazy/Flipper-Xtreme#Known-bugs) | [Install](https://github.com/ClaraCrazy/Flipper-Xtreme#Install) | [Build](https://github.com/ClaraCrazy/Flipper-Xtreme#build-it-yourself) | [Discord](https://discord.gg/flipper-xtreme)
-----

This firmware is a complete overhaul of the [Official Firmware](https://github.com/flipperdevices/flipperzero-firmware), it also features lots of awesome code-bits from [Unleashed](https://github.com/DarkFlippers/unleashed-firmware).

-----
<br>
<h2 align="center">What makes it special?</h2>

<p>If you can't tell... This is a fork of a fork of a fork. 
We have spent many hours perfecting this code even further, and getting the most out of it.

The goal of this Firmware is to regularly bring out amazing updates based on what the community wants, with an actual understanding of whats going on. Fixing bugs that are regularly talked about, removing unstable / broken applications (.FAP) and actually using the level system that just sits abandoned everywhere else.
<br><br>
<i>Thanks to <b>FlipperZero, Unleased Team, RogueMaster, ClaraCrazy, and UberGuidoZ.</b></i>
<br><br>
This firmware is very large because it attempts to include and organize many public asset repos that provide IR, SUB, NFC, IBTN, and other resources. I do not recommend this for well established Flippers! However if you are a new Flipper Operator and would like to take a quick shortcut, this will flash faster than you will find all the resource files.
<br><br>
If you just want the Resources check assets/resources and have fun!
<br><br>
<b>No excuses: I am new to GitHub and coding in general, please let me know if I have not properly attributed your work. Submit a pull request and I will validate and promote your work.</b>
<br><br>
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
- Asset Packs: Are you tired of having to remake your custom animations after every update, switching manifests and having a hard time sharing them, especially once you modify scanning assets too? Those times are over. Scroll down to learn more

- Giving the level system a purpose: Right now, each level unlocks a new wallpaper. More on that below

- Clean upgraded code: Some people wrote updates to certain files. These are... painful, to say the least. Here its all built with perfection in mind and integrated in a mostly clean way. I invite you all to compare the code with theirs.

- Up2Date: This firmware receives updates from a few repositories, not just from its Upstream. If there are functional, but yet un-merged Pull requests on another flipper firmware that are good, they will be in here!


-----
<br>
<h2 align="center">Xtreme Settings:</h2>


We wrote a powerful yet easy-to-use application specifically for our Firmware, that gives you easy-access to all the fancy things we implemented:

<img src="https://user-images.githubusercontent.com/55334727/215137728-529274e8-ab95-4164-a2a0-9ff712c9d3c7.gif" align="left" width="400px"/>

<code>Base Graphics:</code> Change the fallback assets used. Its either SFW (default) or NSFW
<br><code>Asset Pack:</code> Allows you to easily customize your firmware, more on that below 
<br><code>Anim Speed:</code> Speed in which the animations play
<br><code>Cycle Anims:</code> Duration of how long animations are played before switching to next
<br><code>Unlock Anims:</code> Custom setting just for NSFW fallback animations. Figure it out ;)
<br><code>Battery style:</code> Classic Firmware battery style toggle, just at a more convenient place
<br><code>XP Level:</code> Changes your Flippers level
<br><code>SubGhz Extend:</code> Allows you to extend the subghz range beyond what FZ devs planned
<br><code>SubGhz Bypass:</code> Allows you to bypass the subghz region locks of the Flipper

<br clear="left"/>

-----
<br>
<h2 align="center">Animations / Asset Packs:</h2>

We created our own, new & improved Animation / Asset system, that we can finally reveal. It lets you to create and cycle through your own `Asset Packs` with only a few button presses, allowing you to easily load custom Animations and Icons like never before.

<img src="https://user-images.githubusercontent.com/55334727/214010675-9eddb8f5-1dd6-4cf4-a0ee-e37af8b6c933.PNG" align="left" width="200px"/>
You can easily create your own pack, or find some user made ones in the discord channel. Check <a href="https://github.com/ClaraCrazy/Flipper-Xtreme/wiki/1.-File-Formats">here</a> for a tutorial on creating your own. Essentially, we got our own <code>Anims</code> & <code>Icons</code> folders, inside each <code>Asset Pack</code>.

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

<details>
<summary>Our example</summary>

In our case, this is used with the NSFW animations. Dont worry, these are disabled by default because I know not everyone likes to see my / anime tits and thats fine. Anyways.. each level gives a brand new background animation, they also become more and more lewd over time. (Funfact for those reading.. thats why the repository has this warning. Github doesnt like my tits :c)

<p>I just want to simplify, expand, unify, and make the FlipperZero a professional use device. Ya know, where your friends and colleagues don't think you're a porn obsessed weeb. Hack for peace! XO
<br><br>
Full roadmap: https://github.com/IamUSER/Flipper-Fusion/blob/main/documentation/roadmap.md

----
<br>
<h2 align="center">List of changes:</h2>

Note: This repo is always updated with select Xtreme Firmware main branch commits. Thank you to everyone who contribues!
<br><br>
Full changelog: https://github.com/IamUSER/Flipper-Fusion/blob/main/documentation/changelog.md

```txt
[Added in Fusion]

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

- SFW Mode (PRO Mode in Fusion)
- Xtreme App
- Asset Packs
- More UI options
- A new battery display-type
- Scrolling view for long file names in browser
- NSFW Animations tied to the level system. Read more above
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
- SFW / Dummy_mode getting you XP
- Leveling system
- Mood system
```
```txt
[REMOVED]

- Unused Dummy Mode
- Broken apps (bad apple, chess, etc.)
- Tons of unused code from FAPs and system calls
```

----
<br>
<p align="center">
  <img src="https://github.com/IamUSER/Flipper-Fusion/blob/main/images/radioactive.gif?raw=true"><br></p>
<h2 align="center">Install my mutant firmware by building it yourself:</h2>
<h3 align="center">Freshest Firmware is in the <b>Reactor</b> Branch!</h3>
<br><br>
Requires builtin updater app! Upgrade to a custom firmware using the webupdater prior to installing Fusion! Once you have a custom firmware such as Unleashed installed you can use the built in updater to load Fusion.
<br>

```bash
To download the needed tools:
$ git clone --recursive https://github.com/IamUSER/Flipper-Fusion.git
$ cd Flipper-Fusion/

Build apps:
$ ./fbt fap_dist

Build resources:
$ ./fbt resources dolphin_ext

Build firmware:
$ ./fbt COMPACT=1 DEBUG=0 updater_package

```

**NOTE: If you are coming from a different FW, it is recommended to delete / clear your "apps" folder on the SD card prior to updating. This folder houses all the .fap files, which do not update to the correct API versions by default if old ones are present (Thanks flipper devs). This does `NOT` remove any of your saved files!**
<br><br>
If you dont like the default asthetic, ClaraCrazy added a SFW mode (Now PRO Mode) to the Firmware. From the main menu, hit `Arrow UP` and select PRO Mode and now all assets will be stock.
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

```txt
- None at this time.
```

----
<br>
<h2 align="center">Credits:</h2>

<p>
- <a href="https://github.com/flipperdevices/flipperzero-firmware">FlipperZero Team</a> - Stock Firmware and the epic FlipperZero!<br>
- <a href="https://github.com/ClaraCrazy/Flipper-Xtreme">ClaraCrazy</a> - Xtreme Firmware<br>
- <a href="https://github.com/DarkFlippers/unleashed-firmware">DarkFlippers</a> - Unleashed Firmware and Apps<br>
- <a href="https://github.com/RogueMaster/flipperzero-firmware-wPlugins">RogueMaster</a> - w/Plugins<br>
- <a href="https://github.com/UberGuidoZ/Flipper">UberGuidoZ</a> - Centralizer of quality flipper files!<br>


----
<h2 align="center">Contributors</h2>
<p align="center">
  <img src="https://user-images.githubusercontent.com/55334727/212134625-21383102-02f3-453f-b1d7-8a9c65b27612.svg">
</p>

----
## SAST Tools

This helps us a lot, thanks for the free license for this project!

[PVS-Studio](https://pvs-studio.com/en/pvs-studio/?utm_source=github&utm_medium=organic&utm_campaign=open_source) - static analyzer for C, C++, C#, and Java code.

----
<p align="center"> "What we do for ourselves dies with us. What we do for others and the world remains and is immortal.” ― Albert Pine </p>
