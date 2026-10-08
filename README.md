# Amiga 360 Refresh 2026 — PC Feature Edition

![Windows](https://img.shields.io/badge/Windows-PC-0078D4?logo=windows&logoColor=white)
![Backend](https://img.shields.io/badge/backend-Xenia_MouseHook-7c3aed)
![Interface](https://img.shields.io/badge/interface-joypad_%2B_keyboard_%2B_mouse-00b7c3)

![Amiga 360 Refresh PC GUI](https://cf.preview.redd.it/release-amiga-360-refresh-2026-feature-edition-release-v0-f3nflv2jxsth1.png?width=1080&crop=smart&auto=webp&s=4939cee0673300985cd238bf2d0250207414fbae)

The PC edition runs the Xbox 360 guest build through a dedicated Xenia MouseHook backend, preserving the controller-first Amiga360 GUI while adding the things a laptop quite reasonably expects: a real keyboard, a real mouse and a cursor that stays inside the window when asked politely.

It carries the final Xbox storage, CD, profile, input and status-panel work to Windows. The result is technically an emulator running inside another emulator, but it behaves like one application and we have agreed not to stare too hard at the architecture after midnight.

## PC controls

- full Amiga keyboard passthrough, with `Esc` reserved for the Amiga;
- `Page Up` toggles GUI and emulation;
- `Page Down` acts as GUI Back;
- physical mouse capture and confinement;
- middle click releases the physical mouse;
- controller input remains available alongside keyboard and mouse;
- Mixed Legacy, Joystick Port 2 and Mouse Port 1 modes are selectable from the GUI.

## Shared Refresh features

- floppy, ZIP and M3U support with a 20-slot disk swapper;
- DH0–DH3 hardfiles, shared `Software` mounting and profile recovery;
- read-only CD0 ISO mounting through `uaescsi.device`;
- Picasso96 modes up to 1024×768;
- savestates, favourites, previews, themes and GUI music;
- paused-frame GUI backgrounds with smooth transitions;
- live CPU, numeric FPS, sound, disk, CD and floppy activity indicators.

## Install

1. Download the Windows binary ZIP from **Releases**.
2. Extract every file to one writable folder.
3. Run `Avvia A360RF26 PC.exe`.
4. Supply only Amiga media that you legally own.

The launcher and configured Xenia backend belong together. Separating them is an excellent way to rediscover why the package was made in the first place.

## Optional Tools CD

`Amiga360-Tools-CD.iso` is available beside the ZIP as a **separate release asset**. The official binary archive is unchanged.

Mount the ISO from the GUI to access CD0 setup and recovery scripts, iGame Classic and catalogue files, archive/filesystem utilities, wallpapers and manuals. The normal `Software` directory already contains `Amiga360-CD0-Setup` and its `cdrom-handler`; the emulator provides `uaescsi.device` at runtime.

**Tools CD SHA-256:** `BAFD560BDB5768A31C0AC30DF99EA48657E62E9073E0E7A9B2B490E1982C3416`

## Screens and discussion

- [Main release discussion on Reddit / r/360hacks](https://www.reddit.com/r/360hacks/comments/1wyz179/release_amiga_360_refresh_2026_feature_edition/)
- [Release thread on GBAtemp](https://gbatemp.net/threads/amiga-360-refresh-2026-released-for-xbox-360-and-pc.685040/)
- [ConsoleMods Xbox 360 emulator reference](https://consolemods.org/wiki/Xbox_360%3AEmulators) — background on the console ecosystem from which this project came; no affiliation is implied.

![Amiga 360 Refresh interface](https://cf.preview.redd.it/release-amiga-360-refresh-2026-feature-edition-release-v0-tap4iw2jxsth1.png?width=1080&crop=smart&auto=webp&s=d3d74a10f02749bdee4b505f492098fea6f6896c)

## Legal content and project status

No Kickstart ROM, Workbench installation, commercial game, HDF collection or copyrighted music collection is distributed. The project was developed for study and personal satisfaction using legally owned Amiga 500 and Amiga 1200 machines, their Kickstart and Workbench media, and 38 original games.

Do not bundle this emulator, or any part of it, with copyrighted material unless you have the rights holder's authorization. The PC edition remains the experimental branch and may receive deeper backend or core work later; chaos, if any, will be versioned.

## Credits and contact

Core and port lineage: Bernd Schmidt, Toni Wilen, Richard Drummond, Mustafa “GnoStiC” Tufan, Lantus and their contributors. Refresh engineering by Vanni B. Monti-Condesnitt. Xenia keeps its own authorship, license and notices.

Bug reports, mirror notices and source-access requests: `xrest@hotmail.com`

If you enjoy the work, the optional coffee link lives in the packaged README. No popup, no guilt trip, no animated cup following your cursor.
