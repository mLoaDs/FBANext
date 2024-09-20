MagicSeb
August 14,2014
FBNAext v0.2.97.31 

- Games Kaneko Supernova is not working / more
- Fixed a bug with the ARM7 to the previous version, now all games work PGM.
- Endian fix for d_tail2nose, d_mwarr, d_nemesis

some of Kaneko are corrected.

However Suprnova works tjs not -Cyvern etc ..-
----------------------------
MagicSeb
October 03,2013
FBNAext v0.2.97.30 custom 1.0

Update to 0.2.97.30
 
- Dragon Master does not work on 360.
- Playmark games run without problems
- Take the rom pack 0.2.97.29
---------------------------------
MagicSeb
January 22,2013
FBNAext v0.2.97.28 custom 1.1

Most of the fixes are from a previous version (Beta 2.2), I adapted them to the current version.
Thanks to Lantus for doing the work for me

Big Endian FIX :
- d_sys18
- d_tumbleb
- d_yunsun16
- d_pushman
- d_gumbo
- d_unico
- d_terracre
- d_dynduke
- d_armedf
- d_galpanic
- d-nmg5
- d_prehisle
- d_powerins
- d_pass
- d_ohmygod
- d_hyperpac
- d_f1gp
- d_pirates
- d_gotcha
- d_welltris * WARNING, this fix crashes fba if you go back to the menu. 
  Normally, POST 90 games should all work
-----------------------------
MagicSeb
December 31,2012
FBNAext v0.2.97.28 custom 1.0 titles and previews are displayed

- Moonwalker BOOTLEG fix : 100% running now
- Preview and titles OK: Using RomList.cpp from version 0.2.97.27
--------------------------
Lantus
December 18,2012
FBNAext v0.2.97.28

- Added Ganbare Marin-kun to the CPS-1 driver [Barry, smitdogg, The Dumping Union]
- Added Ghost Muncher to the Galaxian driver [Barry, Robbert, Misfitmame]
- Added Bubble Bobble Lost Cave to the Bubble Bobble driver [Barry, Bisboch, Aladar]
- Added bootleg of Carrier Air Wing to the CPS-1 driver [Barry, JacKc, Bonky0013]
- Added various bootlegs of Street Fighter II Champion Edition to the CPS-1 driver [Barry, JacKc, bonky0013]
- Added clone of The Punisher to the CPS-1 driver [JacKc, Artemio Urbina]
- Added clone of Marvel vs. Capcom to the CPS-2 driver [Barry, ranger_lennier, Yohji, Tormod, Smitdogg, The Dumping Union]
- Added clone of X-Men Children of the Atom to the CPS-2 driver [Barry, Bonky0013]
- Added clone of Bagman to the Galaxian driver [Barry, Robbert, Misfitmame]
- Added clone of Frogger to the Galaxian driver [Barry, Robbert, Misfitmame]
- Added clone of Galaxian to the Galaxian driver [Barry, Robbert, Misfitmame]
- Added clone of Moon Cresta to the Galaxian driver [Barry, Robbert]
- Added clone of Scramble to the Galaxian driver [Barry, Robbert, Misfitmame]
- Added clone of Triple Punch to the Galaxian driver [Barry, lucaelia, Siftware]
- Added clone of Fantasia to the Gals Panic driver [JacKc, Brian Troha, The Dumping Union]
- Added clone of Ghosts ‘n Goblins to the driver [JacKc, Antonio Gonzalez Jr., tafoid]
- Added clone of Haunted Castle to the Konami driver [JacKc, Andrew Welburn, Phil Bennett]
- Added clone of Sunset Riders to the Konami driver [JacKc, hap, Dave F]
- Added clone of Sunset Riders to the Konami driver [JacKc, Any, The Dumping Union]
- Added clone of Thunder Zone to the Konami driver [JacKc]
- Added clone of King of Fighters ’97 to the Neo Geo driver [iq_132, smitdogg]
- Added Time’s UP! Demo to the Neo Geo driver [Barry, NGF Dev. Inc, Fred/FRONT]
- Added clone of Ms Pacman to the Pacman driver [JacKc, hap]
- Added three clones of Knights of Valour Superheroes to the PGM driver [JacKc, Joerg Hartenberger, iq_132, smitdogg]
- Added some Ketsui Arrange versions to the PGM driver [JacKc]
- Added clone of Puzzli 2 to the PGM driver [Tormod, Smitdogg, The Dumping Union, JackC, iq_132]
- Added clone of Speed Rumbler to the driver [iq_132, Corrado Tomaselli, JacKc]
- Added clone of Superman to the Taito-X driver [Barry, JacKc, Brian Troha, Dave France, The Dumping Union]
- Added clone of Zero Point to the Unico driver [JacKc, Takahiro Nogi, hap]
- Simulated the protection in Metal Slug X and removed a nasty patch [iq_132]
- Emulated the protection in Lord of Gun and removed a nasty patch [iq_132]
- Emulated protection in Street Fighter II Rainbow Edition (set 1 and 2) and removed a nasty patch [iq_132]
- Emulated protection in Street Fighter II Mega sets and removed a nasty patch [iq_132]
- Emulated protection in Dinosaur Hunter and removed a nasty patch [iq_132]
- Emulated protection in some Warriors of Fate bootlegs and removed nasty patches [iq_132]
- Fix kov command CC (fixes game stage 6) [iq_132]
- Fixed graphics banking in Port Man [Barry, Robbert]
- Added support for the digital volume slider in CPS-2 test screens, also added support for 
  single board games with no digital slider [Barry]
- Added the Turbo mode dip switch to Street Fighter II Alpha Magic F [Barry, MAME]
- Identified various Streety Fighter II Champion Edition bootlegs and game them more 
  descriptive names and descriptions, eliminating the sf2m* naming convention [Barry]
- Improved emulation of bootleg hardware in King of Dragons bootleg [Barry]
- Added variants to the Time Keeper module [Barry]
- Changed UniBIOS 3.0 to the free version release [JacKc]
- Big-endian fixes for some Data East drivers [MagicSeb]
- Updated the ZET and VEZ CPU interfaces [iq_132]
- Improved CPS-2 rom loading [Barry]
- Fixed Japanese Romanization of some game titles [JacKc]
- Improved Visual Studio version reporting and added Windows 8 support to the System Info module [Barry]
- Updated Visual Studio makefile to support Visual Studio 2012, and fixed some related issues [Barry]
- Added support for targeting Windows XP using Visual Studio 2012 via a makefile flag [Barry]
- Updated GCC makefile to 4.7.1 and fixed warnings [Barry]
- Updated the dat file writer to give each dat file a seperate id to ClrMAME gives each a separate profile [Barry]
- Applied libretro patch [Twinaphex]
- Matched the Megadrive sets to MESS 0.147u4 [Barry]
- Synced sets with MAME 0.147u4 [Barry, JacKc]
----------------------------------------
MagicSeb
November 20,2012
FBNAext v0.2.97.27 Taito Sys B fix 

- Taito b games should be fixed : Rambo 3 and Crime City tested and finally works !
- Screen Resize is saved now. You don't have to resize again after restart.
- Arcade Settings changed : Start + RB is used to add coins - Start + Y : go to pause menu
-----------------------------------------------
MagicSeb
November 1,2012
FBNAext v0.2.97.27 fix 

- d_cbuster.cpp : Colorfix + No crash
- d_simpl156.cpp : Sprites is ok but no background ???
- d_supbtime.cpp : Colorfix + No crash
------------------------------------
Lantus
August 26,2012
FBNAext v0.2.97.27

 +Sound Improvements
- Tidied sound chip interfaces, adding support for volume and left/right 
  selection for individual routes. Updated all drivers to support. 
  Many drivers sound much better with these updates [Barry]
- Fixed an issue with multiple YM2203 chips that resulted in static noise in the sound output [Barry]
- Added pan support to Taito drivers that use panning with the YM2610 sound chip [Barry]
- Added pan support to the Darius driver [Barry]
- Added support for an RC filter, and added support to the Galaxian Konami sound based drivers [Barry]
- Fixed various drivers that rendered the MSM5205 sound too fast when the sample rate was greater than 22050Hz [Barry]
- Applied a YM2413 fix from MAME [Barry]
- Added support for a selectable number of voices in the Namco sound module 
  (fixes sound in the Baraduke, Pac Land and Sky Kid drivers [Barry]
- Added multiple chip support to the Sega PCM module, updated Super Monaco Grand Prix 
  to support the extra sound board [Barry]
- Added support for the MSM6585 chip to the MSM5205 core [iq_132]
- Added multiple chip support to the Y8950 interface, and hooked up in the Cybertank driver [Barry]
- Small speedup in the DAC core [iq_132]

- Standardised some CPU interfaces [iq_132]
- Improved Atari slapstic emulation, and updated the Gauntlet driver to support it [iq_132]
- Added driver for Atari Tetris [iq_132]
- Added driver for Cybertank [iq_132]
- Hooked up analog inputs in the Cybertank driver [Barry]
- Added driver for games on Donkey Kong hardware [iq_132]
- Tidied Donkey Kong driver to build with current FB Alpha, and fixed some bugs and crashes [Barry]
- Added driver for Konami Test Board (GX800) [iq_132]
- Added Bang 2 Busters to the Neo Geo driver [lantus]
- Added Treasures of the Carribean to the Neo Geo driver [lantus]
- Added Last Survivor to the Sega X-Board driver [Barry, JacKc, ShouTime, Charles MacDonald, Aaron Giles, 9ofzeven, TrevEB,     Dr. Spankenstein, ghoolster, Surgeville, Tormod, Tjaberg, Waremonger]
- Added Racing Beats to the Taito Z driver [Barry]
- Added bootleg of 1943 to the driver [Barry, JacKc, bonky0013]
- Added clone of Arkanoid to the driver [Barry]
- Added bootleg of Pang! 3 to the CPS-1 driver [JacKc, porchy]
- Added some bootlegs of Street Fighter II to the CPS-1 driver [Barry, JacKc, smitdogg]
- Added clone of Super Street Fighter II to the CPS-2 driver [JacKc]
- Added two clones of Thunder Zone to the Data East drivers [ShouTime, JacKc]
- Added two clones of Dynamite Duke to the driver [JacKc, Arzeno Fabrice]
- Added clone of War of the Bugs or Monsterous Manouvers in a Mushroom Maze to the Galaxian driver [Barry]
- Added clone of Jumping Pop to the driver [Barry, The Dumping Union]
- Added clone of Parodius to the Konami driver [Barry, Andrew Welburn, The Dumping Union]
- Added King of Gladiators Plus to the Neo Geo driver [JacKc]
- Added homebrew WW2 Demo to the Neo Geo driver [Barry]
- Added homebrew Spiderman Intro demo, and added alt sets of TMNT and Dark Wing Duck intro sets to the Neo Geo driver [Barry]
- Added clone of Ketsui Arrange to the PGM driver [JacKc]
- Added clone of Raiden to the driver [Barry, JacKc]
- Added two clones of Fantasy Zone II (System 16C version) to the Sega System 16B driver [Barry]
- Added clone of Turbo Outrun to the Sega Outrun driver [JacKc]
- Added clone of AB Cop to the Sega X-Board driver [JacKc]
- Added clone of GP Rider to the Sega X-Board driver [Barry]
- Added clone of Deer Hunter to the Seta 2 driver [JacKc]
- Added clone of Drift Out to the Taito F2 driver [JacKc, Hammy]
- Added clone of Rygar to the Tecmo driver [JacKc, smitdogg]
- Added clone of Pipi & Bibis / Whoopee!! to the Toaplan 2 driver [Barry, Antonio Gonzalez Jr.]
- Added bootleg of Toki to the driver [Barry, skiltz]
- Added clone of Trojan to the driver [JacKc]
- Fixed bugs in 4 Fun in 1 and Ghostmuncher Galaxian in the Galaxian driver, promoting them to working [Barry]
- Changed Fantastic to use the proper PROM dump in the Galaxian driver, fixing the game colours [Barry]
- Changed Super Bond to use the proper PROM dump in the Galaxian driver, fixing the game colours [Barry]
- Various PGM improvements [iq_132, JacKc]
- Fixed a graphics glitch in the Super Monaco Grand Prix title screen [Barry]
- Fixed issue with Top Speed crashing on driver init [Barry]
- Big-endian fixes for the Cybertank driver [lantus]
- Big-endian fixes for the Sega System 16A and Tecmo drivers [lantus]
- Big-endian fix for Street Fighter II: Magic Delta Turbo sprite x position [lantus]
- Applied various libretro patches [Twinaphex]
- Updated the zlib library to v1.2.7 [Barry]
- Updated the libpng library to v1.5.12 [Barry]
- Matched the Megadrive sets to MESS 0.146u5 [Barry]
- Synced sets with MAME 0.146u5 [Barry]

Xbox Specific Changes
=====================
- All updates from 0.2.97.26 and 0.2.97.27 in whatnew
- Generating Rom list performance improved
- Input presets now save correctly
- Fixed input button issues with 2pp
----------------------------------------
MagicSeb
June 28,2012
FBNAext v0.2.97.26 MagicSeb custom *maj version 3*

- Fixed color bug (rygar, rainbow island...)
- Fixed Titles display
- Fixed Previews display
-----------------------------
Lantus
April 27,2012
FBNAext v0.2.97.25

- CPS-1 Updates, most of the bootlegs now work well and without patches to hack 
  them to work like the originals (brief,incomplete summary below) [Barry, JacKc, bonky_0013, f205v]
- Added some Street Fighter II M bootlegs
- Street Fighter II - Champion Edition (Turbo Hack) now works
- Added an alternate set for Street Fighter II - Champion Edition (Turbo Hack)
- Street Fighter II - Champion Edition (M1 bootleg) now works
- Added support for the dumped Street Fighter II - Champion Edition (Koryu bootleg) graphics roms
- Added Street Fighter II: Magic Delta Turbo (some issues with row-scroll)
- Added an alternate set for Street Fighter II: Magic Delta Turbo
- Added an alternate set for Street Fighter II - Hyper Fighting (bootleg)
- Added a new bootleg of Captain Commando to the driver
- Added new bootlegs of Knights of the Round to the driver
- Daimakai (bootleg) now works
- Carrier Air Wing (bootleg) now works
- King of Dragons (bootleg) now works
- Added Final Crash to the driver
- Emulated the alternative sprite system used in Final Crash and hooked it up in other bootlegs that use it
- Emulated the alternative sound system used in Final Crash and added it to Carrier Air Wing (bootleg) as well
- Emulated the alternative sound system used in Street Fighter: Magic Delta Turbo and added it to a Captain Commando bootleg - and Knights of the Round bootleg as well
- Improved sprite list end detection
- Added optional end of sprite list detection, fixes some more of the bootleg sets
- All Warriors of Fate bootlegs now work properly or at least well
- Added some more Warriors of Fate bootlegs
- All the PIC sets now work, without sound obviously due to no good dump of the PIC data being available
- Tidied the driver
- Removed the CPS Changer region hacks
- Updated the ARM7 core to avoid out of page range accesses [iq_132]
- Added driver for Silver Millenium [iq_132]
- Added bootleg of Dragon Ninja to the DEC-0 driver [Barry]
- Added clone of Super Triv to the Jack the Giantkiller [JacKc]
- Added Neo Castlevania demo to the Neo Geo driver [Barry]
- Added Neo Thunder homebrew game to the Neo Geo driver [iq_132]
- Added NGF Transparency demo to the Neo Geo driver [Barry]
- Added Dragon World: Pretty Chance to the PGM driver (debug builds only) [iq_132]
- Added Ketsui Arrange to the PGM driver [iq_132]
- Added clone of Wonder Boy to the Sega System 1 driver [JacKc]
- Added clone of Rastan to the Misc Taito driver [Barry]
- Added clone of Rastan to the Misc Taito driver [JacKc]
- Tidied the Funky Bee driver [iq_132]
- Tidied the Meijinsen [iq_132]
- Tidied the PGM driver [iq_132]
- Improved protection simulation for some PGM sets [iq_132]
- Fixed sprites alignment in Knights of Valour [iq_132]
- Fixed a crash in PGM rendering code [iq_132]
- Improved sound in the PGM driver [lantus]
- Fixed a crash in the Hunchback sets in the Galaxian driver [Barry]
- Improvements to the Black Tiger driver [iq_132, issues reported by JacKc]
- Fixed savestates in the CPS-3 driver [Twinaphex]
- Fixed a potential crash in the EEPROM module [Twinaphex]
- Fixed custom-sized tile rendering in the generic tiles module [iq_132]
- Big-endian fixes for the ARM CPU interface [lantus]
- Big-endian fixes for the CPS-1, Data East, Neo Geo, Sega and Silver Millenium drivers [lantus]
- Big-endian fix for the Pskiyo 4 driver [Twinaphex]
- Added BRAM support to the PC-Engine driver [kev]
- Added some unicode titles [JacKc]
- Added BDF_CLONE to sfiii3u [iq_132, reported by DsNo]
- Tidied the SNES driver a bit [kev]
- Added SoftFX xBR filters [msbhvn, Hyllian, Barry]
- Fixed a UI issue with unidentified CDs [Barry]
- Rename endian.h to burn_endian.h [Barry]
- Improve portability by checking defines before defining them [Twinaphex]
- Updates to libsnes [Squarepusher2]
- Synced sets with MAME 0.145u7 [Barry]
------------------------------------
lantus
January 12,2011
FBNAext Beta 2.2

- Added video previews. The format must be .wmv and placed in the following directory: 
  GAME:\Videos. (or in the "Videos" directory of the emulator). 
  The name of the video must be .wmv, example: mslug4.wmv. 
  Clone roms will broadcast the video of the "parent" rom. 
  
- Ajout du menu "configuration du stick arcade"
- Added the number of roms found in the listing
- Fixed some bugs in the skin
- The d_raider driver works
- Fixed NEC processor Big Endian
- Core: Fixed space harrier bug for control reversals
- Fixed Ghost N Goblins audio
- Kernel: default nFMInterpolation becomes 1 instead of 3
- Kernel: d_gradius works
- Fixed Pang's ausio bug!
- Kernel: Fixed d_gunsmoke driver
- Kernel: Fix Big endian in d_blockout
- Core: d_tnzs sound works
- No more D3D reset every time you load a rom
- Added correct listening of roms
- Added complete information in case the rom does not launch
- Kernel: Fix Big endian in d_mitchell
- Kernel: Fix Big endian in d_powerins
- Merged into IQ_132s code of PGM games
- Core: Fixed a graphical bug in drgw2
- Possibility to specify several paths (therefore folders) to classify the ROMs
- USB0: USB1: USB2: Hdd1: Memunit0: Memunit1: Dvd: can now be used as directories for roms
-----------------------------
lantus
August 21,2010
FBNAext Beta 2.1

- Performance improvements with Sega X-Board/Y-Board drivers
- Bug fixes in skin movement
- Pressing the Y button on the controller while resizing the screen will return it to its original size
- Fixed bug that hid CPS3 roms when hiding children roms
- Added cache in menus, navigation should be faster
----------------------- 
lantus
August 17,2010
FBNAext Beta 2
  
- Added full support for arcade sticks. Sticks are auto-detected, and back + start displays the in-game menu.
- Added the ability to resize the screen. If you are using an arcade stick, hold "B" + move to stretch the screen, 
  and single move to snap the screen.
- Added the ability to remap an entire system with a default keymap. Each system can be configured differently
- Added 68000 cpu overclock option
- Added rom filter to only show 3 and 4 player games
- Added rom filter to only display "parent" games
- Added saving of the last chosen filter and the position of the last selected rom
- Added right and left triggers for button configuration
- Added error message if your Rom is not correct
- Added OpenMP support for Taito games. ChaseHQ goes from 30fps, to 60 without filters. (Experimental). 
  More optimization in future releases.
- Updated fonts
- Fixed lags in Megadrive games
- Fixed bugs with NeoGeo JAMMA games
- Fixed d_toki.cpp
- Fixed endian in d_aerofgt
- Fixed endian in d_wwfwfest
- Fixed endian in Pang 3 game
- Correction de d_unico (Zero Point/Zero Point 2)
- Fixed d_flgp
- Correction of chelnov
- Correction de Wrestlefest
- Fixed analog stick in opwolf/spacegun/seta deer hunter games (Arkanoid style)
- Fix in d_snk68.cpp IkariIII
- Fix in d_kaneko16.cpp with The Berlin Wall
- Fixed crash in d_hellfire.cpp
- Corrected de f1dream et tigerroad
- Fix in BC Kid
- Fixed color palette in Cave games, like Power Instinct 2, Power Instinct 2, Gawange
- Fixed crashes with some System16 games
- Fixed graphic sprites with CPS1 games
- Fixed reset while paused
- Fixed bug where player 3 was controlling player 4 
----------------------------------
lantus
July 28,2010
FBNAext Beta 2

* Added 68000 overclock option
* Fixed d_aerofgt endian.
* Added filters for 3-4 player only games.
* Added 'Hide Child Roms' option.
* Fixed d_unico (Zero Point/Zero Point 2)
* Fixed d_f1gp.
* Fixed analog in opwolf/spacegun/seta deer hunter games (Arkanoid still doesn't work).
* Fixed d_snk68.cpp – IkariIII
* Fixed crash with berlin wall d_kaneko16.cpp
* Menu now saves last rom and hardware filter used.
* Fixed crash in d_hellfire.cpp
* Fixed in f1dream, tigerroad.
* Fixed in BC Kid.
* Updated 'font'.
* Added left and right triggers in input config
* Fixed d_wwfwfest endian.
* Cave – fixed palette issues with Power Instinct 2, Power Instinct 2, Gawange
* Fixed cracj with some System16 games.
* Fixed gfx sprite with CPS1
* Fixed "reset" with pause.
* Analog stick 3 no longer controls player 4.
* Fixed slowdowns on EU megadrive roms.
* Added support for Arcade Sticks. It will be detected automatically and the Back + Start buttons 
  will display the game menu.
*...
-----------------
lantus
July 02,2010
FBNAext Beta 1

To do:
========
- Optimize the code
- Better interface for controller options
- Fixed minor bugs in rom support
- Cheat codes
- Overclock 68k processor
- Better support for different screen sizes
- Other forgotten things

Bugs
====
- Savestates function may be broken.
- PAL megadrive games have a speed issue. The same rom in USA version will work flawlessly
- Skins issues
-------------------------------------------------------------------------------
On October 4, 2002, FBA-X was born, coded by Lantus and T-maul on the 1st Xbox. 
Today, reformed after 8 years, together with the LSteam, we are proud to present 
FBAnext: FB Alpha for Xbox 360.

About

=====
FB Alpha (Final Burn Alpha) is a multi-arcade emulator based on the Final Burn source code.
FBAnext is a Native port to Xbox 360.
-----------------------------------------------------------
Features
========
- Support for Capcom CPS-1 roms 
- Support for Capcom CPS-2 roms 
- Support for Capcom CPS-3 roms 
- Support for Cave roms 
- Support for Neo geo roms 
- Support for Sega System 16 (and similar systems), System 18, X-Board, Y-Board roms
- Support for Toaplan roms
- Support for Taito 68k roms
- Support for Psikyo 68EC020/SH2 roms
- Support for PGM roms
- Support for Konami roms
- Support for Sega Megadrive roms (savestates are not supported)
- Support for other roms (those that the creator liked)
- Full sound and graphics support
- Multiplayer support (from 1 to 4)
- 100% speed, with most graphics filters
- Support you Savestates
- Ease of use thanks to a simple interface
- Support for almost 3000 roms
- Support for screenshots Titles and Previews
- Support for Video Previews
- Roms filtrables
- 13 software graphic filters
- 2 hardware graphics filters
- Aspect ratio function
- Support des Dip Switch
- Support for Arcade Sticks
- Configurable controller buttons
- Source code available
- Support for Street fighter 3.2 (cps3) 16/9 mode   
----------------------------------------------------

THANKS

=====
Artik - for QA testing/Skin support and general support
XingXing - for providing help and advice on the PGM system.
ekeeke - for help with endian issues and the m68k emulation
iq_132 and the FBAlpha team

r0wdy and Team Avalaunch
------------------------------------
Systeme Emuliert

- Capcom CPS-1
- Capcom CPS-2
- Capcom CPS-3
- Cave
- Neo Geo
- Megadrive
- Sega System 16 (and similar), System 18, X-Board, Y-Board
- Toaplan
- Taito
- Psikyo 68EC020 based hardware
- Autres

