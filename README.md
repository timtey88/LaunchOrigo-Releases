# LaunchOrigo Releases

This repository hosts release binaries and update feeds for [LaunchOrigo](https://github.com/timtey88/LaunchOrigo) — a Launchpad-style app launcher for macOS.

## Latest Release

Download the latest version from the [Releases](../../releases) page.

## System Requirements

- macOS 26.0 or later
- Apple Silicon or Intel Mac

## Installation

1. Download `LaunchOrigo-x.x.x.zip` from the latest release
2. Unzip and move `LaunchOrigo.app` to your Applications folder
3. Launch the app

## Auto-Updates

LaunchOrigo includes built-in auto-update support via [Sparkle](https://sparkle-project.org/). The app checks for updates automatically once per day. You can also manually check via:

- Settings → About → Check for Updates
- Menu bar → Check for Updates

## Release Files

Each release includes:

- `LaunchOrigo-x.x.x.zip` — The signed application bundle
- `appcast.xml` — Sparkle update feed (used by the app to find updates)

## Security

All releases are signed with a valid Apple Developer ID certificate and notarized by Apple.

---

*This repository contains only release artifacts. Source code is available in the main [LaunchOrigo repository](https://github.com/timtey88/LaunchOrigo).*
