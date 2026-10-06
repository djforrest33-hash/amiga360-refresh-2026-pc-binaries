# Amiga 360 Refresh 2026 - PC Feature Edition

**The Xbox-born, controller-first Amiga experience running on PC through a carefully modified Xenia backend, with native keyboard and real mouse support because laptops deserve strange hobbies too.**

Amiga 360 Refresh PC Edition carries the final Xbox Refresh feature set to Windows while keeping the original joypad-first GUI. The guest remains the Xbox 360 build; a dedicated Xenia MouseHook backend supplies the PC input, cursor and host integration needed to make it feel like an actual PC application instead of an emulator running inside another emulator while everyone pretends this is normal.

## Download

Download the complete Windows package from the [PC Feature Edition release](https://github.com/djforrest33-hash/amiga360-refresh-2026-pc-binaries/releases/tag/v1.0-feature-edition-pc). It is one verified ZIP: extract it to a writable folder and run `Avvia A360RF26 PC.exe`.


## What is inside

- The complete Refresh frontend: profiles, previews, favorites, savestates, themes and GUI music.
- Stable floppy, ZIP and M3U handling with a 20-slot disk swapper.
- DH0-DH3 hardfiles, shared Software mounting and saved-profile recovery.
- Read-only CD0 ISO mounting through the resident `uaescsi.device` bridge.
- Picasso96 modes through 1024x768.
- The paused Amiga frame behind every GUI page after emulation begins, with smooth zoom transitions.
- Labelled activity lamps for `SND`, `CPU`, numeric FPS, `DH0`, `CD` and `DF0`-`DF3`.
- Full Amiga keyboard passthrough.
- Page Up to toggle GUI/emulation, Page Down for GUI Back and Escape reserved for the Amiga.
- Physical mouse capture and confinement, with middle click to release it.
- Mixed Legacy, Joystick Port 2 and Mouse Port 1 input modes.

## Source code

The Amiga360/P-UAE source and the small Xenia patch set are maintained separately and can be made available to recognised community and preservation outlets on request. The complete modified Xenia source tree remains a separate asset, keeping the project readable and preventing a 600 MB source archive from arriving dressed as a small frontend update.

## Project status

The PC build is aligned with the final Xbox storage, CD/SCSI, status LED, profile and input fixes. PC-specific development remains the experimental branch and may eventually borrow more ideas from WinUAE or another modern core. If it becomes a monster, it will at least be joypad-first, arcade-friendly and have a very good GUI.

## Legal content is not included

No Kickstart ROM, Workbench installation, commercial game, user hardfile or music collection is distributed. Supply only material you legally own.

The project was developed for study and personal satisfaction using legally owned Amiga 500 and Amiga 1200 computers, their Kickstart and Workbench media, and 38 legally owned original games. Do not use this emulator, or any part of it, in a distribution containing copyrighted material without the rights holder's authorization.

## Credits and license

Core and port lineage: Bernd Schmidt, Toni Wilen, Richard Drummond, Mustafa "GnoStiC" Tufan, Lantus and their contributors. Refresh work by Vanni B. Monti-Condesnitt. Xenia retains its own authorship, license and notices.

The project remains free software under the GNU GPL, with third-party components under their respective licenses.

Bug reports and suggestions: `xrest@hotmail.com`

**Buy Me a Coffee if you like the Work - PayPal.Me @VMontiCondesnitt**

