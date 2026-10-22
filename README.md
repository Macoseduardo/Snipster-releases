# Snipster

A screenshot tool for **Windows and Linux** that replaces the Snipping Tool shortcut.
It runs in the system tray, takes over **Win+Shift+S**, copies every capture to the clipboard,
saves it to your screenshots folder and opens a quick editor (pen, arrow, text, select / cut / copy / paste, crop).

This repository only hosts the downloads. **Latest version: 1.2.0** (2026-10-22)

## Download

| | File |
|---|---|
| **Windows** (installer, recommended) | [Snipster-Setup-1.2.0.exe](https://github.com/Macoseduardo/Snipster-releases/releases/download/v1.2.0/Snipster-Setup-1.2.0.exe) |
| Windows (portable, no install) | [Snipster-1.2.0-windows-portable.zip](https://github.com/Macoseduardo/Snipster-releases/releases/download/v1.2.0/Snipster-1.2.0-windows-portable.zip) |
| **Linux** (AppImage) | [Snipster-1.2.0-x86_64.AppImage](https://github.com/Macoseduardo/Snipster-releases/releases/download/v1.2.0/Snipster-1.2.0-x86_64.AppImage) |

All versions and release notes: [Releases](https://github.com/Macoseduardo/Snipster-releases/releases)

## Install

**Windows:** run the installer. It installs for your user only (no admin rights needed), adds a Start menu
entry and can start Snipster with Windows. Uninstall from *Settings → Apps*. Windows SmartScreen may warn
because the app isn't code-signed: choose *More info → Run anyway*.

**Linux:** make the AppImage executable and run it:

```bash
chmod +x Snipster-1.2.0-x86_64.AppImage
./Snipster-1.2.0-x86_64.AppImage
```

Linux desktops don't let apps take over Super+Shift+S themselves, so add a custom keyboard shortcut in your
system settings that runs:

```
/path/to/Snipster-1.2.0-x86_64.AppImage --capture region
```

## Updates

Snipster checks this page once a day and **asks** before doing anything: download and install (Windows),
open the download page, skip that version, or remind you later. You can also check any time from
*About → Check for updates*, or turn the daily check off in *Capture settings*.
