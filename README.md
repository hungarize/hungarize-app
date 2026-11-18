# Hungarize for Mac

The Hungarize app for macOS (Apple Silicon, macOS 13 or later): Hungarize's Patreon dialogues, notes,
exercises and services in one window.

**Download:** [Hungarize.dmg](https://github.com/hungarize/hungarize-app/releases/latest/download/Hungarize.dmg)

1. Open the DMG and drag Hungarize into the Applications folder.
2. Open Hungarize from Applications. macOS says it couldn't verify the app ("Hungarize" Not Opened): click **Done**.
3. Open System Settings ▸ Privacy & Security (the **Open Settings** shortcut in the DMG window takes you there),
   scroll down to Security, click **Open Anyway** next to "Hungarize" was blocked, and enter your Mac's password.
4. When macOS asks one last time, click **Open Anyway**. From then on Hungarize opens like any other app.

After that the app keeps itself up to date: it checks once a day and offers each new version
(Hungarize ▸ Check for Updates… checks straight away).

This repository holds only the releases and `appcast.xml`, the update feed the app reads.
Every update is signed, and the app installs only updates signed with Hungarize's key.
