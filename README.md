Retrofix - Emulationstation theme for Batocera 5.25+
====================================================

Theme designed by 20Goto10
Version 1.0
First release 31/05/2020
Last updated 9/04/2021


**Retrofix combines two of my loves: vintage video game artwork and Batocera. Sometimes the game art
can be more interesting than the games themselves, so you don't need any games to enjoy Retrofix,
you can add dummy .zip files into the games directories, then scrape, you have a visual
reference library.**

This is the initial release of Retrofix and it's still in its early stages of development.


Examples:
---------

**You can see Retrofix in action here:**


![Tiles view](https://github.com/20GotoTen/es-theme-retrofix/blob/master/_inc/screenshot/Tiles.png "Tiles view")
- Tiles view: https://youtu.be/A2hP1grA_Pg


![Detailed view](https://github.com/20GotoTen/es-theme-retrofix/blob/master/_inc/screenshot/Detailed.png "Detailed view")
- Detailed view: https://youtu.be/cFv1xhQ5-xM

![Boxes view](https://github.com/20GotoTen/es-theme-retrofix/blob/master/_inc/screenshot/Boxes.png "Boxes view")
- Boxes view: https://youtu.be/XLuyA9z8LYA

Supported themes in version 1.0:
--------------------------------

**Theme systems are currently supported, mainly because they have the best art :) other systems supported by Batocera to follow.**

- Master system
- Mega drive (and regional variants)
- Dreamcast (and regional variants)
- Sega Saturn
- Mame
- N64
- Neo Geo
- Neo Geo Pocket Color
- NES
- PC Engine (and regional variants)
- PC Engine CD
- Playstation
- Playstation 2
- PS3
- PSP
- 32X
- Mega CD (and regional variants)
- SG-1000
- Snes (and regional variants)
- Super Grafx
- Amiga
- Atari 800
- Atari 2600
- Atari 5200
- Atari 7800
- Atari Lynx
- Atari Jaguar
- Atari ST
- Laserdisc/Daphne
- Game Gear (and regional variants)
- Gameboy
- Gameboy Advance
- Famicom Disk System
- Intellivision
- Colecovision
- Vectrex
- Sega
- Namco
- Jaleco
- Capcom
- Konami
- Taito
- Atari
- Data East
- Auto Favourites
- SNK
- PC ports
- CPS1
- CPS2
- CPS3
- 3DO
- Odyssey 2
- Images
- 3DO
- Commodore 64
- Gamecube
- MSX
- MSX 2
- OpenBoR
- Wii
- WiiU
- ZX Spectrum
- Atomiswave
- Naomi



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


Gamelist view styles to try:
----------------------------

- **TILES (default):** The default layout. Like Netflix or Prime for retro games! Each game pulls in a thumbnail, Marquee and plays a video clip of the selected game in the background. If no video is scraped, it will show the thumbnail.

- **DETAILED:** A nice balance of speed and visual niceties. Plays the selected video in the background, alongside the game marquee and game overview. Supported by a left-side gamelist, with optional system diagrams, activated in the UI settings (off by default, only SNES, PC Engine, Neo Geo and Master System have these at the moment.

- **GRID:** Displays boxes automatically in a two row configuration. Will be refined in a later update.

- **BOXES:** Game box art configured for each system, which is nice if you love box art / Japanese variations like me. The grids have been autoconfigured for the format of each system's box art, so it's recommended to keep the grid set to AUTO.

Button styles:
--------------

Here you can choose what button style you want to see throughout Retrofix. By default, where available, it will display the button styles for each system selected, including a supporting colour palette.

- **All system buttons:** Uses a button style specific to the system (default, recommended)
- **Generic buttons:** Uses a generic button style across Retrofix.
- **<system name>:** When selected Retrofix will use that button style across all systems.

Show game names on boxes view (yes/no, default: no):
---------------------------------------------------

- **NO:** Shows boxes without game titles.
- **YES:** Shows game titles above the boxes, good for foreign language titles.


Show console art on lists (yes/no, default: no):
-----------------------------------------------

- **NO:** Games list shows a solid grey background.
- **YES:** Games list shows a technical drawing for the selected system (only currently viewable on Master System, Neo Geo, PC Engine, Super Famicom).


Region (mix, eu, jp, us):
------------------------
- **mix:** Uses the theme default region settings (theme default).
- **eu:** Uses European logos if available.
- **jp:** Uses Japanese logos if available.
- **us:** Uses US logos if available.


Use darker mode (yes/no, default: no):
-----------------------------------------------

- **NO:** Uses a dark grey system-wide colour setting.
- **YES:** Uses a black system-wide colour setting.



Coming soon:
------------

- Splash screen.
- System theme music.
- Metadata icons for all systems to complete. Currently those without custom metadata icons fallback to generic.
- Buttonsets for all supported systems.


Thanks and credits
------------------
- The Batocera team (https://batocera.org) and the Batocera Discord artwork community for helping those who need it and being great overall.
- jdorigao (https://github.com/jdorigao) for his Alekfull theme which got me interested developing themes in the first place.
- Darknior (https://github.com/Darknior) for his amazing RVGM theme and his thoroughly documented comments which were very helpful.
- fabricecaruso (https://github.com/fabricecaruso) for the continued improvements and additions to Emulationstation which make it so much fun.
- Ordovice (https://github.com/ordovice) for support and his contibutions to regional settings.
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
