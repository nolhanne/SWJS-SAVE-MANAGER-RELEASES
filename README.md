# Jedi Survivor Save Manager

**A Windows save-swapping companion for STAR WARS Jedi: Survivor speedrunners.**

[![Download latest release](https://img.shields.io/github/v/release/nolhanne/SWJS-SAVE-MANAGER-RELEASES?label=Download&style=for-the-badge)](https://github.com/nolhanne/SWJS-SAVE-MANAGER-RELEASES/releases/latest/download/JSSM-3.2.14.exe)

## Download & run

[**Download JSSM-3.2.14.exe**](https://github.com/nolhanne/SWJS-SAVE-MANAGER-RELEASES/releases/latest/download/JSSM-3.2.14.exe) and double-click to launch. No installation, Python or Git required.

## Features

- Searchable save library with expandable NJ, NJ+, IL and community route collections.
- Replace an existing save slot and remove its matching in-game backups.
- Display and copy the previous save timestamp.
- Protect important slots and restore original main saves from recovery history.
- Add your own practice saves.
- Automatic update checks on launch.

## How to use

1. Open the game and return to the main menu.
2. Launch Save Manager, choose a library save, then select a disposable target slot.
3. Confirm replacement, and load the slot in the game.

Only the original main save is retained in recovery; its associated game backups are deleted. Cross-slot compatibility has not been verified for every save. Test on an expendable slot first.

## Updates & data

The app automatically checks for updates on startup. Accept an available update to open the official download in your browser and close the current application. Launch the newly downloaded EXE. On launch, the app can offer to move verified earlier releases in the same folder to the Recycle Bin; it only does so with your confirmation. It does not replace or execute downloaded program files. If the update check fails, the current version remains usable. Your library, settings and recovery data are kept separately in `%LOCALAPPDATA%\JediSurvivorPracticeManager` so they survive updates.

The executable is not code-signed. Windows may show a SmartScreen warning. Only download from this repository.

## Feedback

Found a bug or have a suggestion? [Open an issue](https://github.com/nolhanne/SWJS-SAVE-MANAGER-RELEASES/issues).

Community-made tool, not affiliated with EA, Respawn or Lucasfilm.
