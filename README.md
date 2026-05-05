<img width="1536" height="1024" alt="DUSTBUNNiES" src="https://github.com/user-attachments/assets/30c42459-bf4e-4f7e-a821-4b1bbebcfa5e" />

**DUSTBUNNiES** is a curated holding archive for **undatted, unclassified, and otherwise homeless ROMs, disk images, firmware, tools, and oddities** that do not currently belong in any known or official DAT set.

Think of it as a **staging archive**:  
Files live here while they are unidentified, poorly classified, uncatalogued, or awaiting proper sorting into a real collection.

This is **not** a trash pile. Everything here is intentionally kept, categorized, and tracked.

---

## Purpose

- Hold files that:
  - Do not match any known DAT
  - Are not yet understood or identified
  - Belong to obscure, incomplete, or abandoned ecosystems
  - Are tools, dumps, formats, or fragments with no clear home
- Provide:
  - A structured place for “unknowns”
  - A way to track and gradually migrate items into proper sets
  - A historical record of “stuff that didn’t fit anywhere else (yet)”

If a file eventually gets properly identified and adopted into a real collection, **it should leave DUSTBUNNiES**.

---

## DEEP FOLDER STRUCTURE WARNING

This collection, simply through natural categorization and sorting, will always have its share of deep nested folders and long filenames. To ensure that things do not get out of hand, I have written my own tools to scan this collection before datting to ensure:
- from the top-level folder of this collection, the longest full path length, including the filename, should fall within 200 characters
- there may be the odd exception where I've allowed it to go slightly above 200, but the **hard upper limit is 210 characters max**
- 210 characters allows enough wiggle room for the "invisible" portions of the file paths that the user will never see (eg. "C:/ROMVault/DatRoot/"), or the server-side cloud path prefix of a cloud-connected folder, which i've seen up to 40 characters in length for an online host like OneDrive. Also, some scripting languages and older apps will forbid exceeding the 260-char path length limit even if you have it bypassed.

Therefore, I am stating that it is a REQUIREMENT to physically place the "DUSTBUNNiES" top-level folder location in the root of your storage volume, and work off of it from there.  If you choose to alter this placement, you are on your own for any path length issues that could surface when working on the collection with other tools and apps (RomVault will do just fine though).

### How I handle extremely long filenames: 

First, I ensure the folder path naming is optimized as best as possible. Maintaining tight folder naming is critical.

If that doesn't help, the general order of operations for shortening filenames are as follows:
1. condense empty space between brackets: ") (" becomes ")("
2. condense empty space between separators such as commas, semicolons, dashes:  "this, that" becomes "this,that" and "what - why" becomes "what-why"
3. trim superfluous wording:  "T-En by DatGuy" becomes "T-En DatGuy" and "Game needs 512MB of RAM to operate" becomes "512MB RAM reqd"
4. adjust long-form dates:  "December 25 2020" becomes "2020-12-25"
5. if the name is still too long, begin trimming non-title words and info from the filename, in order of importance to the overall filename (author names usually are the first to go at this point).

It's a delicate balance when removing or trimming filenames. You want to preserve as much information in the filename as possible but the realization is all the extra fluff the creators put into the filename would have been better in a readme, but not everyone always has enough reason to do so. Also, readme's are easy to lose and discard as unwanted. Just ask someone like No-Intro where all the readme's are stored for the roms they put into their datfiles. :P

Regardless of my ensuring that the length of the paths and files stay within the 260-chracter Windows limit, YOU MUST ENABLE LONG PATH LENGTH SUPPORT in Windows if you know what's good for you.  It does not cost you anything at all, other than simply enabling it.  It's a simple registry addition, anyone can do it.

here's a step by step illustrated guide: [How to Enable Win32 Long Paths in Windows 11](https://www.thewindowsclub.com/how-to-enable-or-disable-win32-long-paths-in-windows-11-10)

the official docs: [Microsoft - Maximum Path Length Limitation](https://learn.microsoft.com/en-us/windows/win32/fileio/maximum-file-path-limitation?tabs=registry)

---

## Collection Structure

DUSTBUNNiES is split into several high-level thematic groups, each with its own internal taxonomy.

- Amiga
- Amiga Collections
- Commodore
- Commodore Collections
- Core
- Core Collections
- Disc
---

## 🖥️ DUSTBUNNiES-Amiga

Focused on **Amiga-related disk formats, tools, and odd artifacts** that don’t exist in clean TOSEC/No-Intro/Redump-style sets.

### Subcategories include (by format or purpose):
060, A2500, ADF, ADZ, AMOS, ARC, ASM, BIN, CAPS, Collections, CT, CTR, EXE, FDI, HDF, HFE, IMG, IPF, LHA, LZH, LZX, MFM, RDF, ROM, SCP, USS, ZOM, ZOO.

---

## 🖥️ DUSTBUNNiES-Commodore

### Everything Commodore-adjacent that doesn’t exist in clean, curated sets yet:
- C= OS Vision
- C16-C116-Plus4
- C64
- C64 DTV
- C64 Mini
- C65
- C128
- CBM-II
- CBM 510
- CBM 610
- CBM PET
- COMAL
- Commander X16
- commodore.software (website backup)
- CPM
- GeoWorks
- MEGA65
- VIC20

---

## 🖥️ **Core** and **Core - Collections**
- Core contains non-optical roms and files, where the collections are larger archives containing entire curated collections that have not yet been datted.
- **Arcade:** Pinball, Taito, 
- **Computer:**
    - Acorn, Amstrad, Apollo Guidance Computer, Apple, Applied Technology, Atari, Batong Sunsonic, BBG Electronics, Berkeley, Computer Corporation, BINBUG-based machines, Bung Dr PC Jr, Camputers, Canon, Casio, CCE, Central Data 2650, Cidelsa, Coleco, COMX, DEC, Dick Smith, Digital Research, DOS, DOSV, Dragon Data, Elektor TV Games Computer, Elektronika, Elektronska Industrija Nis, ELF Linux, Emerson, Enterprise, Exelvision, Fairchild, Foenix, Fujitsu, Galaksija, Heathkit, Hitachi, Hofacker MIKIT 2650, IBM PC, IBM PC 8088-86, Interton VC 4000, Jupiter, Kaypro, KingWon, Matra-Hachette, Mattel, MGT, Microboard Computer Development System, Microkey, Micronique, Motorola, MSX, NABU, National, NCR Decision Mate V, ncurses, NEC, Nintendo, Olivetti, Panasonic Panaword U1, PCem, Peters Plus, Philips, PHUNSY, PIPBUG-based machines, Raspberry Pi, Ravensburger Selbstbaucomputer (aka 2650 Minimal Computer), RCA, Research UNIX, Robotron, Sanyo, Sega, Sharp, Signetics Instructor 50, Signetics TWIN, Sinclair, Sony, Sord, Subor, SVI Spectravideo, Tandy, Tangerine, Telmac, Texas Instruments, Thomson, Timex, Toshiba, VEB Robotron-Elektronik Dresden, Video Technology, Videoton, VTech, Windows (Japan), WonderSoft COMPAC, Xerox, Yuxing, ZhongSuo
- **Computer-Digital:**
    - Fantasy Consoles, RetroArch BIOS
- **Console:**
    - APF, Atari, Bally, Capcom, Casio, Coleco, Epoch, Funtech, GCE, Konix, Leapfrog, Magnavox, Mattel, Microsoft, Motion Activated Gaming Console, NEC, Nintendo, Philips, RCA, Sega, Sony, Tectoy, View-Master Interactive Vision, VTech.
- **Handhelds:**
    - Analogue, Arduboy, Atari, Bandai, Benesse, Bit Corporation, Cassiopeia, Creatronic, Evercade, EXEQ, Game & Watch, Gamebuino, GamePark, GCE, HP, LeapFrog, Nikko, Nintendo, Nokia, Palm OS, Panic, Pimoroni, Pokemon TCG, Pokitto Oy, Sega, SNK, Sony, Texas Instruments, VTech, Welback, WonderWitch.
- **Music:**
    - AmigaRemix, OCRemix, OverClocked ReMoved, Remix.Kwed.org

---

## 💿 Disc

Optical disc images and disc-based ecosystems that don’t exist in clean Redump, No-Intro or any other Non-ABCXYZ or known sets:
- Commodore Amiga
- Mattel Intellivision
- Nintendo Gamecube
- Nintendo Wii
- Philips CD-i
- Sega Dreamcast
- Sony PlayStation 2
- Sony PlayStation Portable
- Win95

---

## Curation Rules

- This is **not** an unsorted dumping ground.
- Everything here should:
  - Be categorized
  - Have a reason to exist here
  - Be a candidate for future identification or migration
- If something gets a proper home elsewhere, **it should be removed from DUSTBUNNiES**.

---

## Philosophy

- Real archives are built from uncertainty first.  
- DUSTBUNNiES is where uncertainty is allowed to exist — neatly.

---
## Contributing

Have some unknown files that still don't match with the dats? Pack your unknown files up into separate folders named for their system, then create a single archive for each system (zip/7z/rar/tar/gz are all acceptable).  Simply upload them to the Mega Uploads folder provided below. You don't need an account, simply drag and drop into the webpage! We'll give this a try and hopefully I won't see any abuse of the uploads folder.

If you would like to be recognized for your donations, include a note inside the uploads and I'll be sure to add you to a thank you list on this page.

Use the MEGA uploads folder here:

[![mega_uploads](https://github.com/user-attachments/assets/bdd28a8c-6db1-42cc-b0e6-6dc1250b8f8a)](https://mega.nz/filerequest/CgJbFGg8ZCI) 

---

## Support

If these tools, dats, or archives save you time, consider supporting the work:

<a href="https://buymeacoffee.com/eggmansworld">
  <img src="https://cdn.buymeacoffee.com/buttons/v2/default-orange.png" height="45" alt="Buy Me a Coffee">
</a>

---

## Licensing

Original source code, scripts, tooling, and hand-authored documentation and
metadata in this repository are licensed under the MIT License.

Archived game data, binaries, firmware, media assets, and other third-party
materials are **not** covered by the MIT License and remain the property of
their respective copyright holders.

See the `LICENSE` and `NOTICE` files for full details and scope clarification.
