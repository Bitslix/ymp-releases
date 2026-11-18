# YMP – YouTube Moderator Panel

Public downloads and update feed for **YMP**, a desktop app for moderating YouTube live chats and greeting viewers.

## Download

Get the latest installer from the **[Releases page](https://github.com/Bitslix/ymp-releases/releases/latest)**.

| Platform | File |
| --- | --- |
| Windows (x64) | `…_x64-setup.exe` |

Linux and macOS builds will follow later.

## Release channels

| Channel | Versions | For whom |
| --- | --- | --- |
| **Stable** | `1.2.0` | Everyone. Tested releases. |
| **Beta** | `1.3.0-beta.1` | Early access to new features. May contain bugs. |

Beta releases are marked as *Pre-release* on the Releases page. Beta users also receive every newer stable release.

## Updates

YMP checks for updates by itself. Open **Settings → App Info** to:

- choose the update channel (Stable or Beta),
- turn the automatic check on or off and set how often it runs,
- check for updates manually and install them with one click.

Updates are never installed without your confirmation, so a running stream is never interrupted. Every update is signed and verified before installation.

## Repository layout

| Path | Purpose |
| --- | --- |
| `channels/stable.json` | Update manifest for the Stable channel (read by the app). |
| `channels/beta.json` | Update manifest for the Beta channel (read by the app). |

The manifests are written by the release tooling. Please do not edit them by hand.
