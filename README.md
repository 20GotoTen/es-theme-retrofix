Retrofix - Emulationstation theme for Batocera 5.25+
====================================================

Theme designed by 20Goto10
Version 2.0
First release 31/05/2020
Last updated 16/03/2023


**Retrofix combines two of my loves: vintage video game artwork and Batocera. Sometimes the game art
can be more interesting than the games themselves, so you don't need any games to enjoy Retrofix,
you can add dummy .zip files into the games directories, then scrape, you have a visual
reference library.**


Examples:
---------

**You can see Retrofix in action here (v2 to videos to follow):**

![Main menu](https://github.com/20GotoTen/es-theme-retrofix/blob/master/_inc/screenshot/Main%20menu.png "Main menu")


![Tiles view](https://github.com/20GotoTen/es-theme-retrofix/blob/master/_inc/screenshot/Tiles.png "Tiles view")
- Tiles view: https://youtu.be/A2hP1grA_Pg


![Detailed view](https://github.com/20GotoTen/es-theme-retrofix/blob/master/_inc/screenshot/Detailed.png "Detailed view")
- Detailed view: https://youtu.be/cFv1xhQ5-xM

![Boxes view](https://github.com/20GotoTen/es-theme-retrofix/blob/master/_inc/screenshot/Boxes.png "Boxes view")
- Boxes view: https://youtu.be/XLuyA9z8LYA

Supported themes in version 2.0:
--------------------------------

**Theme systems are currently supported, mainly because they have the best art :) other systems supported by Batocera to follow.**

- Sega Master system
- Sega Mega Drive (and regional variants)
- Sega Dreamcast (and regional variants)
- Sega Saturn
- Mame
- N64
- N64DD
- Neo Geo
- Neo Geo CD
- Neo Geo Pocket Color
- NES
- PC Engine (and regional variants)
- PC Engine CD
- PlayStation
- PlayStation 2
- PlayStation 3
- PSP
- PS Vita
- Sega 32X
- Sega Mega CD (and regional variants)
- Sega SG-1000
- Super Famicom / Super Nintendo (and regional variants)
- SNES-MSU1
- SatellaView
- Nintendo DS
- Nintendo Switch
- Nintendo Virtualboy
- Super Grafx
- NEC PC-FX
- Atari 800
- Atari 2600
- Atari 5200
- Atari 7800
- Atari Lynx
- Atari Jaguar
- Atari ST
- Atari XE
- Laserdisc/Daphne
- Game Gear (and regional variants)
- Gameboy
- Super Gameboy
- Gameboy Advance
- Famicom Disk System
- Fairchild Channel F
- Intellivision
- Colecovision
- Coleco Adam
- Vectrex
- Sega
- Namco
- Jaleco
- Capcom
- Konami
- Taito
- Technos
- Tecmo
- Atari
- Data East
- Alpha Denshi
- Banpresto
- Eighting
- Exidy
- Cave
- Gaelco
- Gottlieb
- Hikaru
- IGS
- Incredible Technologies
- Irem
- Kaneko
- Midway
- Mitchell
- Nichibutsu
- Nintendo
- NMK
- Psikyo
- Sammy
- Seibu Kaihatsu
- Semicom
- Toaplan
- Universal
- Visco
- Video System Co
- Auto Favourites
- SNK
- PC ports
- CPS1
- CPS2
- CPS3
- 3DO
- Odyssey 2 / Philips Videpac
- Philips Videopac +
- 3DO
- Commodore 64
- Gamecube
- MSX
- MSX 1
- MSX 2
- MSX 2+
- MSX Turbo R
- OpenBoR
- Nintendo Wii
- Nintendo WiiU
- Triforce
- Sinclair ZX Spectrum
- Sinclair ZX-81
- Atomiswave
- Naomi
- Naomi 2
- Sega STV
- Amiga 500
- Amiga CD32
- Amiga CDTV
- Amstrad CPC
- Amstrad GX4000
- AFP M1000
- Apple II
- Astrocade
- BBC Micro
- Vic 20
- Commodore 128
- Commodore Plus4
- Commodore PET
- Final Burn Neo
- Fujitsu FM-7
- Fujitsu FM Towns
- Game & Watch
- Sega Model 2
- Sega Model 3
- MSU-MD
- NEC PC8800
- NEC PC9800
- Pico-8
- Pygame
- Sam Coupe
- Scummvm
- Super Cassette Vision
- Solarus
- Sufami Turbo
- TI-99
- TIC-80
- Windows
- Wonderswan
- Wonderswan Color
- Sharp X1
- Sharp x68000
- Xbox
- Xbox 360



Also included in /root is splash video.


Scraping images for Retrofix:
-----------------------------

The theme relies on the following assets being scraped, and it ALL can be done
directly in Batocera, no external scraper required!

 - Thumbnail
 - Marquee
 - Image
 - Video (optional, worth it if you have the disk space)

**Don't use Scraped image mixes. They will look terrible with this theme.**



SETTINGS
--------


Gamelist view styles to try:
----------------------------

- **TILES (default):** The default layout. Like Netflix or Prime for retro games! Each game pulls in a thumbnail, Marquee and plays a video clip of the selected game in the background. If no video is scraped, it will show the thumbnail.

- **DETAILED:** A nice balance of speed and visual niceties. Plays the selected video in the background, alongside the game marquee and game overview. Supported by a left-side gamelist.

- **DETAILED BOXART:** As above, but with a slightly tweaked layout to to accommodate box art.

- **GRID:** Displays boxes automatically in a two row configuration. Will be refined in a later update.

- **BOXES:** Game box art configured for each system, which is nice if you love box art / Japanese variations like me. The grids have been autoconfigured for the format of each system's box art, so it's recommended to keep the grid set to AUTO.


Main Menu / System views video delay:
----------------------

If you've scraped videos, Retrofix will display these as backgrounds across the system and gamelist views. Here you can determine if and when they show.

- **2 Seconds (default):** The scraped image will be replaced by the scraped video after 2 seconds.
- **5 Seconds:** The scraped image will be replaced by the scraped video after 5 seconds.
- **Video off:** Only the scraped image will show.


System logos:
-------------

- **mix:** Uses the theme default (my preferred mix). This is the theme default.
- **eu:** Uses European logos if available.z
- **jp:** Uses Japanese logos if available.
- **us:** Uses US logos if available.


Batocera logo:
--------------

- **Show logo:** Shows the Batocera logo across all menu screens.
- **Hide logo:** Shows the Batocera logo across all menu screens.

Animations:
-----------

To users of lower-powered devices such as the Raspberry Pi, you may want to turn off animations for a speedier experience.

- **Animations on:** Turn on the animations (theme default).
- **Animations off:** Turn off the animations.


Scanlines:
-----------

Display a scanline overlay over the screenshots and videos displayed in individual system views.

- **No scanlines:** Don't show scanlines (theme default).
- **Light scanlines:** Show light scanlines over images and videos in individual system views.
- **Dark scanlines:** Show darker scanlines over images and videos in individual system views.



Button set:
-----------

Here you can choose what button style you want to see throughout Retrofix. By default, where available, it will display the button styles for each system selected, including a supporting colour palette.

- **Unique (default):** Uses a button style specific to the system (default, recommended)
- **Red/Blue/Black/Cyan/Green/Yellow buttons:** Uses a generic button style in your chosen colour across Retrofix.
- **<system name>:** When selected Retrofix will use that button style across all of your systems.


Primary / Secondary button graphic:
-----------------------------------

Retrofix uses a custom help system (english at v2 launch) that allows you to set the theme to the specific buttons you set when you configured your controller. That way, the button graphics in Retrofix match your configuation (either A, B, X or Y).


UI modes:
---------

- **Grey mode (default):** Uses a dark grey system-wide colour setting.
- **Darker mode:** Uses a darker system-wide colour setting.



Thanks and credits
------------------
- The Batocera team (https://batocera.org) and the Batocera Discord artwork community for helping those who need it and being great overall.
- jdorigao (https://github.com/jdorigao) for his Alekfull theme which got me interested developing themes in the first place.
- Darknior (https://github.com/Darknior) for his amazing RVGM theme and his thoroughly documented comments which were very helpful.
- fabricecaruso (https://github.com/fabricecaruso) for the continued improvements and additions to Emulationstation which make it so much fun.
- Ordovice (https://github.com/ordovice) for support and his contibutions to regional settings.
- Dan Patrick for filling in some logo gaps with his mindblowing platform logo set (https://forums.launchbox-app.com/files/file/3402-v2-platform-logos-professionally-redrawn-official-versions-new-bigbox-defaults/)
- The game artists themselves for creating over 40 years of memorable and influential artwork which has inspired generations, and inspired me to want to show it all off.


Notice:
-------
- All system logos, game artwork, screenshots and trademarks are copyright of their respective owners. 
- Commercial distribution is prohibited.
- The inclusion of this theme in "all-in-one" or "preloaded" distributions is prohibited.


Licence
-------
**Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**
https://creativecommons.org/licenses/by-nc-sa/4.0/

![Creative Commons Licence](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png "Creative Commons Licence")

Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License

You are free to:

- **Share:** copy and redistribute the material in any medium or format
- **Adapt:** remix, transform, and build upon the material

**Under the following terms:**

**Attribution:** You must give appropriate credit, provide a link to the license, and indicate if
changes were made. You may do so in any reasonable manner, but not in any way that suggests the
licensor endorses you or your use.

**NonCommercial:** You may not use the material for commercial purposes.

**ShareAlike:** If you remix, transform, or build upon the material, you must distribute your
contributions under the same license as the original.

No additional restrictions — You may not apply legal terms or technological measures that legally
restrict others from doing anything the license permits.
