<p align="center">
  <img src="assets/icon.png" width="128" alt="LaunchOrigo">
</p>

<h1 align="center">LaunchOrigo</h1>

<p align="center">
  A faster, more customizable Launchpad replacement for macOS.
</p>

<p align="center">
  <a href="../../releases/latest"><img src="https://img.shields.io/github/v/release/timtey88/LaunchOrigo-Releases?style=flat" alt="Latest Release"></a>&nbsp;
  <img src="https://img.shields.io/badge/macOS-26.0+-000?style=flat&logo=apple" alt="macOS 26.0+">&nbsp;
  <img src="https://img.shields.io/badge/license-Proprietary-blue?style=flat" alt="License">
</p>

---

## About

LaunchOrigo replaces the macOS Launchpad with a faster, more customizable grid that stays out of your way until you need it. Press a global hotkey, find your app, launch it.

## Features

- **Global hotkey** — open the overlay from anywhere
- **Keyboard-first** — arrow keys, type-to-search, return to launch
- **Drag-and-drop organization** — reorder apps and group them into folders
- **Customizable interface** — background styles, grid size, page mode
- **Update delivery** — built-in Sparkle updater; use Check for Updates
- **Export / import** — JSON layout and selected preferences; current version-2 backups do not embed wallpaper images

## System Requirements

- macOS 26.0 or later
- Apple Silicon or Intel Mac

## Installation

1. Download `LaunchOrigo-x.x.x.zip` from the [latest release](https://github.com/timtey88/LaunchOrigo-Releases/releases/latest)
2. Unzip and move `LaunchOrigo.app` to your Applications folder
3. Launch the app

On first open, macOS may show a Gatekeeper dialog. Click **Open** — the app is signed with a Developer ID certificate and notarized by Apple.

## Updates

Use [Sparkle](https://sparkle-project.org/) to check manually. Automatic checks default to off in the reviewed source; do not rely on a guaranteed daily background check. Choose:

- Settings → About → Check for Updates
- Menu bar → Check for Updates

## Maintainer publication notes

Publish the signed final ZIP under the matching release tag before updating the feed. Sparkle reads [the GitHub Pages appcast](https://timtey88.github.io/LaunchOrigo-Releases/appcast.xml), so the validated new item must also be deployed in this repository's root `appcast.xml`. Adding `appcast.xml` only as a GitHub Release attachment does not update that URL. Verify Pages deployment, archive URL, byte length, signature, build and minimum OS before marking delivery complete. Preserve previous useful items and immutable released archives.

The 7 October 2026 documentation review inspected source/local feed, not installed release binaries or remote Pages settings. Signing/notarization/update delivery must be verified for each new release; these notes are not certification of a newly tested artifact.

## Security

- Signed with **Apple Developer ID Application** certificate
- **Notarized** by Apple for macOS Gatekeeper
- Sparkle updates verified with an EdDSA public key
- No tracking or analytics

---

*This repository contains only release artifacts. The source code is private.*
