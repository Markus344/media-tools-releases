# Media Tools — downloads

Installers for **Media Tools**, a small app that prepares Spotify and YouTube media as local files for ProPresenter and other presentation or audio software, and turns chord sheets into ProPresenter slide text. It runs on your own computer in its own window and is in Norwegian.

## Download

Open the [latest release](https://github.com/Markus344/media-tools-releases/releases/latest) and download the file for your computer:

- **Windows 10/11 (64-bit):** `Media-Tools-Setup-<version>.exe`. Run it, then open Media Tools from the Start menu or the desktop.
- **Mac with Apple Silicon (M1 or newer), macOS 14 or newer:** `Media-Tools-Mac-Apple-Silicon-<version>.dmg`. Open it, drag **Media Tools** to **Applications** (Programmer), then open it from there. The first start takes a few extra seconds while the app sets up its download engine.
- **Mac with an Intel processor:** version 3.0 does not run on Intel Macs. Keep using [2.8.0](https://github.com/Markus344/media-tools-releases/releases/tag/v2.8.0) (`Media-Tools-Mac-2.8.0.zip`).

Each release also lists the SHA-256 checksums of its files in `SHA256SUMS.txt`.

## First launch

The installers are not signed yet, so the computer may warn you the first time:

- **Windows:** if SmartScreen says "Windows protected your PC", choose **More info**, then **Run anyway**.
- **Mac:** if macOS says the app cannot be opened, go to **System Settings → Privacy & Security** and choose **Open Anyway**.

Do not turn off your computer's security protections.

## Updates

Media Tools tells you when a new version is published here. Download the new installer and run it (Windows), or drag the new app to Applications and replace the old one (Mac). Your settings, download history and downloaded media are kept. Updating from 2.x: the Spotify Client ID has to be pasted once more.

The download engine (yt-dlp) updates itself when the app opens. If YouTube downloads stop working, choose **Se etter oppdatering** under **Nedlastingsmotor** in the app. If the app says a tool is missing, **Vis detaljer** under **Nedlastingsmotor** shows what it answered.

## Please note

Only download recordings you own or have permission to use. Media Tools does not bypass paid access, DRM or account restrictions. It is independent of Spotify, YouTube and Renewed Vision (ProPresenter).

The source code is kept in a private repository.
