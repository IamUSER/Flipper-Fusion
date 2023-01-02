<h1 align="center"><p>&#9762; Flipper <code>Fusion</code> Firmware &#9762;</p></h1>

<p align="center">
  <img src="https://github.com/IamUSER/Flipper-Fusion/blob/main/hackerdolphin512.png?raw=true">
<br>
A.K.A. Ugly Porpoise
</p>

-----
<br>
<h2 align="center">What makes it special?</h2>

<p>If you can't tell... This is a fork of a fork of a fork. 
<br>
<br>
<i>Thanks to <b>FlipperZero, Unleased Team, RogueMaster, ClaraCrazy, and UberGuidoZ.</b></i>
<br>
<br>
This firmware is very large because it attempts to include and organize many public asset repos that provide ir, sub, nfc, ibutton, and other useful files. It <b>IS</b> going to bloat your device if you already have these files saved to SD. 
<br>
<br>
<b>No excuses: I am new to GitHub and coding in general, please let me know if I have not properly attributed your work. Submit a pull request and I will validate and promote your work.</b>
</p>

----
<br>
<h2 align="center">Roadmap:</h2>

<p>I just want to simplify, expand, unify, and make the FlipperZero a professional use device. 
<br>
Ya know, where your friends and colleagues don't think you're a porn obsessed weeb. 
<br>
Hack for peace! XO

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
If you dont like the default asthetic, ClaraCrazy added an SFW mode (Now OEM Mode) to the Firmware. From the main menu, hit `Arrow UP` and select OEM Mode and now all assets will be stock.

-----
<br>
<h2 align="center">List of changes:</h2>

Note: This repo is always updated with Xtreme and upstream repos. No need to mention all those here. We will only mention **our** changes that we can actually be credited for, unlike *others*

```txt
[Added]

- SFW Mode (Now called OEM Mode in Fusion)
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

```txt
- <a href="https://github.com/flipperdevices/flipperzero-firmware">FlipperZero Team</a> - Stock Firmware and the epic FlipperZero!
- <a href="https://github.com/ClaraCrazy/Flipper-Xtreme">ClaraCrazy</a> - Xtreme Firmware
- <a href="urlhttps://github.com/RogueMaster/flipperzero-firmware-wPlugins">RogueMaster</a> - w/Plugins
- <a href="https://github.com/UberGuidoZ/Flipper">UberGuidoZ</a> - Centralizer of quality flipper files!
```

